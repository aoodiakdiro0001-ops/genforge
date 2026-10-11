# ⚙️ GenForge — Micro-SaaS Generators (MIT)

One-click developer generators. **100% client-side** — nothing leaves the browser.

## Tools (7)

1. **🚫 .gitignore** — 15 stacks (node, python, go, java, php, rust, OSs,
   editors, docker, terraform), merged + de-duplicated, download.
2. **🐳 docker-compose** — node/postgres/mysql/redis/mongo/nginx services,
   ports, env, volumes, restart policy → valid v3.8 YAML.
3. **🖥️ Server configs** — nginx / Apache / Caddy reverse-proxy +
   free-SSL (certbot) hints.
4. **🔑 Secrets** — CSPRNG passwords + JWT secrets, Apache `{SHA}htpasswd`
   lines (SubtleCrypto), base64 ⇄ text, SHA-256/512.
5. **🔄 JSON** — validate/prettify/minify + convert to **TypeScript**,
   **Go structs**, **Python dataclasses** (recursive inference).
6. **🌐 Subnet calculator** — CIDR → network/broadcast/mask/wildcard/
   usable range + host count (/31//32 aware).
7. **🎫 JWT decoder** — header/payload decode with `alg=none` forgery warning.

## Money

- **Ads:** `CONFIG.ads` (`client`+`slot` AdSense or Carbon) → corner units
  + top slot; empty = tasteful placeholder. Dev traffic = high CPC.
- **Donate:** `CONFIG.pay` — BTC + USDT-TRC20 live, `bmc` username for
  Buy-Me-a-Coffee button (empty = hidden).

## Contact / Owner

- 📧 baranavisat@gmail.com · 📞 +90 531 326 37 22 · WhatsApp
- BTC `bc1q8dhtdrndxsl70e97t8grydfe6pjue37zrhzf6c`
- USDT-TRC20 `TLWdTjqqogkXNEXGiPWsGdjFP6ioycxeWW`

## Run

```bash
cd genforge
python3 -m http.server 8080
```

## License

MIT.
