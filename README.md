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
- **Stablecoin, Altcoin, Private key / Seed phrase, Hot wallet, Cold wallet, NFT**

### Очікуваний результат:
Базове розуміння основних понять та специфіки роботи сфери криптовалют.

### Корисні матеріали:
- [Blockchain](https://www.investopedia.com/terms/b/blockchain.asp)
- [Hash](https://corporatefinanceinstitute.com/resources/cryptocurrency/hash-function/)
- [Ethereum](https://trusteeglobal.com/academy/kryptovalyuta-ethereum-shho-cze-ta-v-chomu-yiyi-sut/?s=ethereum)
- [Ethereum](https://trusteeglobal.com/academy/kryptovalyuta-ethereum-shho-cze-ta-v-chomu-yiyi-sut/?s=ethereum)
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

### Функціональність:
- Розробити контракт що має мінімум **двох власників**.
- Можливість **додавати нового власника**, якщо **більше 50%** поточних власників погоджуються.
- Реалізувати функції:
  - `mint(address to, uint amount)` — випуск нових токенів.
  - `burn(uint amount)` — спалення токенів з власного балансу.

### Очікуваний результат:
Чітке розуміння всіх можливостей solidity, вміння створювати нові ф-ї в смарт-контракті.

---

## ✅ 4. Скрипти та робота з ETH

### Завдання:
- Написати скрипт, який:
  - Отримає **баланс ETH** певної адреси.
  - Здійснить **переказ ETH** між двома адресами.
- Створити контракт із **конструктором**, який приймає параметри при деплої.
- Через скрипт:
  - Задеплоїти токен з переданими параметрами.
  - Зробити `mint` певної кількості токенів.
  - Переказати їх на обрану адресу.

### Корисні матеріали:
- [ethers.js](https://docs.ethers.org/)
- RPC-провайдери (Infura, Alchemy)

---

> ⚠️ **Порада:** Постійно експериментуйте з кодом. Не бійтеся помилок — найкраще навчання відбувається через практику! Також не соромтесь і шукайте самі додаткові матеріали до теми, і памʼятайте - chat gpt не завжди каже правду :)
