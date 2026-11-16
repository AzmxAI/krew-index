# MAQPNA krew index

A [custom krew index](https://krew.sigs.k8s.io/docs/user-guide/custom-indexes/) for the `kubectl maqpna` plugin.

```sh
kubectl krew index add maqpna https://github.com/AzmxAI/krew-index.git
kubectl krew install maqpna/maqpna
kubectl maqpna dev up
```

Update with `kubectl krew upgrade`. The plugin archives are the signed releases at
[AzmxAI/maqpna-releases](https://github.com/AzmxAI/maqpna-releases); each manifest pins their SHA256.

MAQPNA is a self-hosted runtime for AI agent security and governance by Kosa8 Labs: https://maqpna.com ·
[Docs](https://docs.maqpna.com). It is commercial, closed-source software under the licence shipped in each
archive; the Community edition is free for one cluster. This index lives outside the central krew-index
because that index takes open-source plugins only.
