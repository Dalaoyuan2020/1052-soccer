# 1052-soccer ⚽ — World Cup 2026 Watch × AI

A lightweight **static web app** for following the **2026 FIFA World Cup** (USA · Canada · Mexico, 48 teams, June 11 – July 19, 2026). It brings the schedule, group standings, an **odds-based AI win/draw/loss prediction**, and daily news together in one clean page.

> 一个轻量级**静态网页**，把 2026 世界杯的赛程、积分榜、**基于赔率的 AI 胜负预测**和每日新闻整合在一起。

## ✨ Features
- 📅 **Schedule** — fixtures with local kickoff times
- 📊 **Standings** — group-stage tables
- 🤖 **Odds → AI Prediction** — win / draw / loss probabilities derived from bookmaker odds (de-vig implied probability), shown as a probability bar
- 📰 **Daily News** — match and tournament news cards

## 🧠 How the prediction works
The prediction converts decimal bookmaker odds to implied probabilities and removes the bookmaker margin (de-vig), giving a real-time, data-driven win/draw/loss estimate. Odds are the market's distilled consensus, which makes them a strong, simple baseline.

## 🚀 Usage
Pure static, zero dependencies — just open `index.html` in any browser.

Deploy free on any static host (drag-and-drop):
- Cloudflare Pages / Netlify / Vercel
- or GitHub Pages

## 🗺️ Roadmap
- [ ] Live data feeds (schedule / scores / standings, real-time odds, news)
- [ ] Auto-fill all group-stage and knockout fixtures
- [ ] Favorite-team tracking
- [ ] Match-day reminders

## 📄 License
MIT — see [LICENSE](LICENSE).

---
*Built as a fun, open project for the 2026 World Cup. Data shown in this demo is illustrative; live feeds are on the roadmap.*
