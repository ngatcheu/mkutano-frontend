Tout menbre de groupe dans créer sa feature selon le model suivant: feature_DITXX chez moi jai feature_DIT01
Etant sur votre branche : feature_DIT-XX

1 - git pull origin develop

Vous effectuez vos modification ensuite sur votre branche puis :

2 - git  add  .
3 - git  commit  -m  "DIT_XX  votre message qui decrit vos ajouts"
4 - git push ou  git push --set-upstream origin feature_DITXX

Une fois que vous êtes sure que votre code compil bien avec vos ajout intégrés a ceux recuperes en ligne sur la branche develop,
Vous ouvrez une merge request de votre branche vers la branche develop.