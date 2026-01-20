# prod-bowchat
To access from localhost : 
debasmita13@DESKTOP-2HHQS11:~/work/prod-bowchat$ kubectl port-forward deploy/prod-bowchat-web 3000:3000 -n prod-bowchat
curl localhost:3000
