# 🚀 План навчання для криптанів (Solidity / Ethereum)

## ✅ 1. Теоретична база

### Основні поняття:
- **Blockchain** — що це таке, для чого він використовується, які задачі вирішує, які його особливості.
- **Hash function, hash** — що це таке, які властивості.
- **Ethereum** — специфіка роботи блокчейну Ethereum, загальне розуміння його роботи.
- **ETH** — нативна криптовалюта Ethereum, призначення.
- **Smart Contract** — що це, для чого, як працює, які задачі вирішує.
- **Gas Fee / Gas Price** — чому транзакції платні, як формується ціна.
- **ERC-20 Token** — стандарт токенів Ethereum, їхні властивості, чому існує такий стандарт.
- **Stablecoin, Altcoin, Private key / Seed phrase, Hot wallet, Cold wallet, NFT** - розібратися та розумітися в цих термінах.

### Очікуваний результат:
Базове розуміння основних понять та специфіки роботи сфери криптовалют.

### Корисні матеріали:
- [Blockchain](https://www.investopedia.com/terms/b/blockchain.asp)
- [Hash](https://corporatefinanceinstitute.com/resources/cryptocurrency/hash-function/)
- [Ethereum old](https://trusteeglobal.com/academy/kryptovalyuta-ethereum-shho-cze-ta-v-chomu-yiyi-sut/?s=ethereum)
- [Ethereum new](https://www.coinbase.com/learn/crypto-basics/what-is-ethereum)
- [Смарт контракт](https://forklog.com/cryptorium/chto-takoe-smart-kontrakt)
- [Gas](https://trusteeglobal.com/academy/gaz-efiriumu-i-kryptovalyuty/?s=ethereum)

---

## ✅ 2. Практика: перший ERC-20 токен

### Кроки:
1. Написати простий смарт-контракт ERC-20 (можна на базі OpenZeppelin).
2. Скомпілювати його в Remix або Truffle.
3. Задеплоїти у тестову мережу (Goerli, Sepolia або інша).
4. Отримати тестові ETH через faucet.
5. Перевірити транзакції у [Etherscan](https://etherscan.io).
6. Оволодіти базовою функціональністю [Etherscan](https://etherscan.io).

### Очікуваний результат:
Загальне розуміння того як розробляються та деплояться смарт-контракти. Базові навички користування блокчейн-експлорером.

### Корисні матеріали:
- [MetaMask](https://metamask.io/)
- [Remix](https://remix.ethereum.org/)
- [OpenZeppelin](https://www.openzeppelin.com/)
- [Etherscan](https://etherscan.io)
- [Sepolia faucet](https://sepolia-faucet.pk910.de/)
- [Google faucet](https://cloud.google.com/application/web3/faucet/ethereum)
- [Solidity docs](https://docs.soliditylang.org/en/v0.8.30/)

---

## ✅ 3. Розширення: нові функції токену

### Завдання:
- Розробити контракт що має мінімум **двох власників**.
- Реалізувати можливість **додавати нового власника** в задеплоєному контракті, якщо **більше 50%** поточних власників погоджуються.
- Реалізувати функції:
  - випуску нових токенів.
  - спалення вже існуючих токенів з власного балансу.
- Написати контракт, який розподіляє ERC-20 токени описані іншим контрактом ([Приклад](https://stermi.medium.com/how-to-create-an-erc20-token-and-a-solidity-vendor-contract-to-sell-buy-your-own-token-8882808dd905)).

### Очікуваний результат:
Чітке розуміння всіх можливостей solidity, вміння створювати нові методи в смарт-контракті.

---

## ✅ 4. Web3 – написання cкриптів для роботи з ETH

### Завдання:
- Написати скрипт, який:
  - Отримає **баланс ETH** певної адреси.
  - Здійснить **переказ ETH** між двома адресами.
- Навчитись деплоїти контракт програмно з можливістю передачі потрібних параметрів в **конструктор**.
- Через скрипт:
  - Зробити `mint` певної кількості токенів.
  - Переказати їх на обрану адресу.
  - Переглянути баланс токену по заданій адресі.

### Корисні матеріали:
- [ethers.js](https://docs.ethers.org/)
- RPC-провайдери (Infura, Alchemy)

---

> ⚠️ **Порада:** Постійно експериментуйте з кодом. Не бійтеся помилок — найкраще навчання відбувається через практику! Також не соромтесь і шукайте самі додаткові матеріали до теми, і памʼятайте, що chat gpt – не дає вам розуміння та обізнаність в певній темі, він дає вже готове рішення, яке залишається лише використати. Ми цінуємо більш широкий погляд на речі.
