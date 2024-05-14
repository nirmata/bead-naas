# bead-naas
The Example Bead can be used to build more complex examples of using BACK Stack. In this example, we use Namespace-as-a-Service by providing the correct policy sets and backstage catalog entries to provide self-serve NaaS.

The example structure is as follows:
- `argocd` folder holds the app to which BACK Stack's ArgoCD will point to.
- `backstage` folder holds the template/resources/components which make up the Bead to be used when imported in Backstage.
