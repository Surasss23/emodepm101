# CheatGpt

A minimal, comedy-first chatbot parody. Visitors choose **CEO (₹59)** or **Normal Person (free)**, complete a short profile, answer five multiple-choice questions, and receive a personalized fictional roast.

## Run locally
Open `index.html` in a browser. The QR code uses the QRCode.js CDN.

## Deploy
Enable GitHub Pages for the repository and select the branch containing `index.html` as the source.

## Payment prototype notice
The CEO QR encodes a ₹59 UPI payment request to the configured UPI ID. The prototype does **not** verify payments server-side. The “I've completed payment” control is a self-confirmation for testing and must not be treated as proof of payment. Before accepting real payments, integrate a payment provider or a secure server-side UPI verification workflow. Never rely on client-side confirmation to grant paid access.

## Privacy
The current prototype keeps profile answers in browser memory only and does not send them to a server.

## Disclaimer
CheatGpt is fictional entertainment. Its jokes about NASA, public figures, companies, and espionage are parody, not factual claims.
