kubectl get secret mysqlrootpass -o jsonpath='{.data.rootpass}' | base64 --decode
