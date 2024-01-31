```mermaid
graph
  7dd5a1c0-85bc-3aba-cc75-b72532d50d0d((srf-hello...)):::Namespace
  3e7b14de-5cff-4591-a92d-3a46ab297975((srf-hello...)):::Pod
  6d62acb2-4e2a-45e8-b338-501492a26c32((srf-hello...)):::ReplicaSet
  9979abd7-103b-4bed-faae-5447ebef59e3((srf-hello...)):::Container
  17f17d76-c4f1-c409-5cab-f9746ec8b1dd((api.srf-p...)):::Cluster
  6d62acb2-4e2a-45e8-b338-501492a26c32 -- Pod --> 3e7b14de-5cff-4591-a92d-3a46ab297975
  3e7b14de-5cff-4591-a92d-3a46ab297975 -- Container --> 9979abd7-103b-4bed-faae-5447ebef59e3
  17f17d76-c4f1-c409-5cab-f9746ec8b1dd -- Namespace --> 7dd5a1c0-85bc-3aba-cc75-b72532d50d0d
  7dd5a1c0-85bc-3aba-cc75-b72532d50d0d -- ReplicaSet --> 6d62acb2-4e2a-45e8-b338-501492a26c32
```
