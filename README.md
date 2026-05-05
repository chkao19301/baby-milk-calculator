# 🍼 Baby Milk Calculator

A simple web tool to calculate the best mix of hot and cold water when preparing formula, so the blended temperature stays in a comfortable range (42–48°C).

## ✨ Features

- **Smart calculation**: Finds the best hot/cold water ratio in **10 ml** steps
- **Temperature control**: Targets **45°C** and keeps the mix within **42–48°C**
- **Bilingual UI**: Traditional Chinese and English; switch anytime
- **Responsive UI**: Mobile-friendly layout with a dark theme
- **Instant results**: Updates as soon as you choose your parameters

## 🎯 How to use

1. Pick total volume (**120**, **150**, **180**, or **210 ml**)
2. Pick hot water temperature (**70**, **80**, **90**, or **100°C**)
3. Pick cold water temperature (**16**, **18**, **20**, **22**, **24**, or **26°C**)
4. Tap **Calculate best 10 ml ratio**
5. Read the suggested hot/cold amounts and the estimated mixed temperature

## 🔧 Technical notes

- **Client-side only**: HTML, CSS, and JavaScript—no backend required
- **Physics**: Uses a simple heat-balance mix formula:

  ```
  mixed_temp = (hot_ml × hot_temp + cold_ml × cold_temp) / total_ml
  ```

- **Optimization**: Tries all valid **10 ml** combinations and picks the one closest to **45°C**

## 📱 Who it’s for

- Parents who want a quick formula-water temperature estimate
- Caregivers who want to stay in a safe, comfortable band
- Anyone who wants a practical ratio without mental math

## 🌐 Browser support

Works in modern browsers (Chrome, Firefox, Safari, Edge, etc.)

## 📄 License

See [LICENSE](LICENSE).

## 💡 Disclaimer

- For reference only—follow your formula brand’s preparation instructions
- Results are approximate; actual temperature can vary with environment and measurement
- If hot/cold inputs are unrealistic, there may be **no** mix that lands in the target range

---

**中文說明**：[README.zh-TW.md](README.zh-TW.md)
