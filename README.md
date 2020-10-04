# infra-git-flow


## Testing: 


### 1)

    Align `sandbox`, `dev` and `master` branches. Alignment starts from `master` branch.

### 2)

    Create 2 feature branches, `A` and `B` from `master`, merge it to `sandbox`, than `de`v. On `sandbox`, merge `A`, than merge `B`. Once both are merged, on `dev` firstly merge `B`, than `A`, and then on `master` merge `A`, then `B`.

### 3)

    Create a a feature branch `C` from master. merge it to `sandbox` and `dev`.

### 4)

    Create a feature branch `D` (before merging `C`), try to merge it on `sandbox` and `dev`. Merge `C` and `D` on master.

### 5)

    Create a feature branch called `cleanup`, remove the unneccessary files, then merge it to `sandbox`, `dev` and `master`.