# 🔥 Welche Benchmarks für welche Agenten?

## 📌 Übersichtstabelle

| **Agenten-Typ** | **HumanEval** | **HumanEval-X** | **SWE-bench Mini** | **SWE-bench Pro** | **Agentic Workflows** | **MiniWoB++** | **Vision/GUI Grounding** | **Audio TTS/SST** | **Web-Recherche** | **Security-Audits** | **Code-Review** | **UX-Testing** | **Performance-Optimierung** | **Architektur-Review** | **Chaos-Engineering** |
|-----------------|---------------|-----------------|---------------------|-------------------|-----------------------|---------------|---------------------------|-------------------|-------------------|---------------------|----------------|----------------|---------------------------|---------------------|---------------------|
| **Hermes** | ❌ Nein | ❌ Nein | ⚠️ Optional | ✅ **Ja** | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Prometheus** | ❌ Nein | ❌ Nein | ⚠️ Optional | ✅ **Ja** | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein |
| **Zeus** | ❌ Nein | ❌ Nein | ⚠️ Optional | ✅ **Ja** | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ✅ **Ja** | ❌ Nein | ❌ Nein | ✅ **Ja** | ✅ **Ja** |
| **Atlas** | ✅ **Ja** | ✅ **Ja** | ✅ **Ja** | ✅ **Ja** | ⚠️ Optional | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Iris** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ⚠️ Optional | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein |
| **Janus** | ✅ **Ja** | ✅ **Ja** | ✅ **Ja** | ✅ **Ja** | ⚠️ Optional | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Hades** | ✅ **Ja** | ✅ **Ja** | ✅ **Ja** | ✅ **Ja** | ⚠️ Optional | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Asclepius** | ✅ **Ja** | ✅ **Ja** | ✅ **Ja** | ✅ **Ja** | ⚠️ Optional | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Athena** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Argus** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Daedalus** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Hermes Scout** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Multimedia-Looker** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Audio-Agent** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Web-Recherche-Agent** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Metis** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein |
| **Themis** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Aegis** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Hephaestus** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein |
| **Chronos** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein |
| **Nemesis** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** |
| **Apollo** | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ❌ Nein | ✅ **Ja** | ❌ Nein | ❌ Nein | ❌ Nein |

## 📌 Wichtige Erkenntnisse

### ✅ **SWE-bench Pro ist das WICHTIGSTE für `opencode CLI`!**
- **SWE-bench Pro** testet **komplexe, mehrstufige Agenten-Aufgaben** (genau wie `opencode CLI` sie ausführt).
- **SWE-bench Pro** ist der **härteste Benchmark für Agenten-Systeme 2026**.
- **SWE-bench Pro** ist der **Standard für Agenten-Benchmarks**.

### ⚠️ **HumanEval ist wichtig, aber nur für reine Code-Generierung**
- **HumanEval** testet **einfache Code-Generierung** (z.B. Python-Funktionen).
- **HumanEval** ist **nicht agenten-relevant** (nur Code, keine Agenten-Aufgaben).
- **HumanEval-X** ist **wichtig für Atlas, Janus, Hades** (mehrere Sprachen).

### ✅ **Agentic Workflows sind das WICHTIGSTE für Agenten-Systeme!**
- **Agentic Workflows** testen **mehrstufige Agenten-Aufgaben** (z.B. \"Installiere Redis + Konfiguriere + Teste\").
- **Agentic Workflows** sind **der Standard für Agenten-Benchmarks 2026**.
- **Agentic Workflows** sind **real-world-nah** (echte Workflows!).

### 🔥 **Für `opencode CLI` sind diese Benchmarks am wichtigsten:**
1. **SWE-bench Pro** (🥇 **Wichtigster Benchmark!**)
2. **Agentic Workflows** (🥈 **Wichtig für Agenten-Systeme!**)
3. **SWE-bench Mini** (⚠️ **Optional, aber nützlich**)
4. **HumanEval-X** (⚠️ **Optional, für Atlas/Janus/Hades**)

### 🔥 **Für `Code-Swarm` sind diese Benchmarks am wichtigsten:**
1. **SWE-bench Pro** (🥇 **Wichtigster Benchmark!**)
2. **Agentic Workflows** (🥈 **Wichtig für Agenten-Systeme!**)
3. **Validation Superlayer** (⚠️ **Zeus, Aegis, Hephaestus, Chronos, Nemesis**)
4. **Feedback-Loops & Self-Improvement** (⚠️ **Memory Layer, Error Tracking**)

