Toby Kurniawan

Sorry about the merge conflicts - I made a mistake earlier. Accidently used the wrong base as the rebase branch at first. Anyways, basic run down of rebase commands:

1) First checkout the feature branch (aka develop)
2) Rebase against the 'rebase' branch
![Screen Shot 2021-09-17 at 1 44 58 PM](https://user-images.githubusercontent.com/38872576/133831583-6f2d97e4-6602-4ff1-b23c-c245c94203cc.png)

3) Checkout the rebase branch
4) Place the changes onto the rebase branch, thus commits c1 and c2 should still come after c3 and c4
![Screen Shot 2021-09-17 at 1 46 13 PM](https://user-images.githubusercontent.com/38872576/133831720-61b54ff9-7495-4174-851a-bbc9373597ed.png)
