
# Gasy RP

Serveur Nosy Lava RP + migration 


## Authors

- [Kiady Tsitohaina](https://github.com/Jok4ir)
- [Setra Solofoniaina](https://github.com/Setra-Solofoniaina)
- [Henintsoa Rasoloson](https://github.com/hkhoumal)

## Deployment

Branch usages:

- The branch ` staging ` is used for production.
- The branch ` master ` is used to store all modifications where are merged all features.

When modifications within `master` is all confirmed, we can merge all his modifications into branch `staging`

To do that, just run the command
```
git checkout staging
git merge --ff-only master
```

To Verify that all modifications is migrated to the branch `staging`, 
run 

```
git log
```
and compare last commits with last commits in `master` branch.