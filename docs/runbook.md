# Runbook

> Fill in every TODO with exact commands. / Попълнете всяко TODO с точни команди.

## Start locally / Локално стартиране

npm install
npm run dev

## Check that it works / Проверка, че работи

curl -I http://localhost:3000

## Run the tests / Тестове

npm test

## When something breaks / Когато нещо се счупи

npm run logs # или преглед на конзолата, където върви npm run dev
lsof -i :3000
rm -rf node_modules package-lock.json && npm install
