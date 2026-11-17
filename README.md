# sample-payment-frame

> [!WARNING]
> **This sample is retired and is no longer hosted.** The live demo that used to run on Heroku has been taken down, and the hardcoded environment key in this sample no longer accepts tokenization requests.
>
> This sample uses non-secure tokenization: it sends only the environment key, with no nonce, timestamp, certificate token, or signature. Non-secure tokenization was deprecated on October 31, 2026, with end of life on December 31, 2028. Do not use this code as the basis for a new integration.
>
> For new integrations, use the [Checkout SDK](https://developer.spreedly.com/docs/tokenization). If you maintain an existing iFrame integration, see the [iFrame payment form](https://developer.spreedly.com/docs/iframe-payment-form) guide for secure tokenization, and turn on Enhanced Security for your environment in app.spreedly.com.

An example implementation of a payment page using the Spreedly iFrame payment collection form.

All logic is contained in `index.html`. The other files in this repo
exist to support deploying this app to Heroku. If you've cloned the
repo locally, you can just open `index.html` in your browser.
