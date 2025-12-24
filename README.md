TOPOPAY_CONFIG = {
    MERCHANT_ID: 'M241119VIMSY545', // Ganti dengan Merchant ID TokoPay Anda
    SECRET_KEY: 'bd2e466c7c87db503aa7b3782f80a2fb20d4897403d6109510d6e8ae315c152f',   // Ganti dengan Secret Key TokoPay Anda
    API_BASE_URL: 'https://api.tokopay.id/v1',
    WEBHOOK_URL: process.env.WEBHOOK_URL || `http://${getServerIP()}:${process.env.WEBHOOK_PORT || 3000}/webhook/tokopay`, // URL webhook otomatis menggunakan IP server
    PAYMENT_METHOD: 'QRIS_CUSTOM'
};

# SandiMf


<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sancrusader/sancrusader/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sancrusader/sancrusader/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/sancrusader/sancrusader/output/github-snake.svg" />
</picture>
