# android-paging-rxjava
### Code for the Paging Codelab: https://codelabs.developers.google.com/codelabs/android-paging/          
# ___Uses RxJava Instead of LiveData___

__Steps :__   
#### The branches denote progress converting the existing repo to Paging in the following order :

1. Paging
2. Paging_with_boundry_callback
3. paging_with_rxjava

### Best way to follow 

1. See the changes to convert the repo from Normal List to pagedList https://github.com/erluxman/android-paging/compare/master...erluxman:paging
2. See the changes to implement the boundry callbacks https://github.com/erluxman/android-paging/compare/paging...erluxman:paging_with_boundry_callbacks
3. See the changes to replace LiveData with RxJava observables (Gradle versions upgrade are optional).  https://github.com/erluxman/android-paging/compare/paging_with_boundry_callbacks...erluxman:paging_with_rxjava

![DEMO](https://media.giphy.com/media/YNCoeCwInGPbIiIFL4/giphy.gif)
