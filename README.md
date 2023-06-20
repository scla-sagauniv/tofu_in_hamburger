# tofu_in_hamburger
ハックツハッカソンモサカップ　豆腐入りハンバーグ

## 🚀 How do we boot up the app

```
docker-compose up db
```

```
docker-compose up server
```

```
migrate -database 'mysql://root:password@tcp(db:3306)/tofu_in_hamburger' -path db/migrations up
```

```
Execute INSERT statement to seed the initial data
```

```
npm run dev
```

Access to http://localhost:3000/send and http://localhost:3000/confirmation simultaneously to observe how server streaming is working!
