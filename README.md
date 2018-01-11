# finance-jupyter
Finance notebooks
First attempt in using Github 
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MatsGustavsson/finance-jupyter/master?urlpath=apps/SequentialStructure_clean.ipynb)
The difference is in the URL itself. This is the "basic" binder link:

https://mybinder.org/v2/gh/MatsGustavsson/finance-jupyter/master

and if you want to enable / use the "appmode" plugin, you add the following to the end:

?urlpath=apps/SequentialStructure.ipynb

so the full length would be:

https://mybinder.org/v2/gh/MatsGustavsson/finance-jupyter/master?urlpath=apps/SequentialStructure.ipynb
urlpath is a parameter that BinderHub knows how to use - it basically just changes whatever comes after the address of your Binder instance (replacing /tree with whatever else). In this case appmode has been enable to be easily accessible via the url so it works here!

Also if multiple people click a binder link two totally different binder instances will be created for them, so no worries there!

(gonna close this issue since I think the original problem has been resolved!)
