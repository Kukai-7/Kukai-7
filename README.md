<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=26&duration=3000&pause=1200&color=B33A2B&vCenter=true&width=720&height=48&lines=Hi+there%2C+I%27m+Elis%C3%A9e;Data+%26+Corporate+Finance;Opening+Europe+for+RootClean+AI;Between+Europe+and+China;Humanities+first%2C+data+second" alt="Hi there, I'm Elisée" /></a>

<p><b>Data &amp; corporate finance, between Europe and China.</b> Humanities first, data second.</p>

<p>
  <a href="https://www.linkedin.com/in/elis%C3%A9e-t-2150892a2/"><img src="https://img.shields.io/badge/LinkedIn-Elis%C3%A9e-24292F?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://huggingface.co/Kukai-7"><img src="https://img.shields.io/badge/Hugging_Face-Kukai--7-2F4B7C?style=flat-square&logo=huggingface&logoColor=white" alt="Hugging Face" /></a>
  <img src="https://img.shields.io/badge/Focus-Europe_%C3%97_China-B33A2B?style=flat-square" alt="Focus: Europe x China" />
</p>

I studied History before I studied finance, and it shows: I like data that tells a story someone can act on.

I'm doing an **MSc in Data & Corporate Finance at Audencia** and I help **RootClean AI**, an early-stage AI startup, open its European market. Before that, China: sales and sourcing for an electronics trader in Shenzhen, from the Canton Fair to supplier negotiations; a semester of finance at Shenzhen University; AI market intelligence in Nanjing; and cost control inside a Dongguan factory, reporting to the CFO.

> *À cœur vaillant rien d'impossible*

---

### Experience

| | Role | When | Where |
|---|---|---|---|
| **RootClean AI** | GTM Lead EMEA (early-stage startup, small founding team) | Oct 2026 → now | New York · Europe |
| **Easy Factory** | Cost Controlling Intern, Finance (reporting to the CFO) | May → Sept 2026 | Dongguan, China |
| **Shenzhen University × SAFTI** | Exchange semester, Master in Finance | Fall 2025 | Shenzhen, China |
| **AirNet** | Corporate Strategy Intern, AI & Market Intelligence | June → Sept 2025 | Nanjing, China |
| **E-Ran Technology** | Overseas Sales & Sourcing Intern | July 2024 → Jan 2025 | Shenzhen, China |
| **ENGIE** | Credit & Collection Analyst, ENGIE portfolio (via EOS France) | Mar → June 2024 | France |
| **Audencia** | Grande École Programme · MSc Data & Corporate Finance | Current | France |

---

### Featured work

#### [Drivers of the Nikkei 225](https://github.com/Kukai-7/nikkei-225-drivers) · Econometrics

Which macro-financial forces move Japan's benchmark index, do they survive Japan's own pricing factors, and did the 2026 oil shock change the answer?

- 250 monthly observations, full diagnostics, structural break tests on the 2026 oil shock
- Fama-French Japan factors plus momentum, model selection by F-tests, AIC and BIC
- **Result:** the yen and the S&P 500 explain about 64% of monthly moves; oil only matters after March 2026; the final factor model reaches an adjusted R² of 0.91

`Python` `statsmodels` `SciPy` `Pandas` `Matplotlib`

#### [BoJ Tone Tracker](https://huggingface.co/spaces/Kukai-7/boj-tone-tracker) · NLP on central bank language

Hawkish or dovish? A RoBERTa classifier reads every Bank of Japan policy statement since 2013, sentence by sentence, and the resulting tone index is set against the Nikkei 225. Runs entirely in the browser: the chart opens instantly, and the model runs on the GPU when the browser allows it.

- 133 statements, 2,591 sentences, scraped from the BoJ and cleaned
- Pre-trained central bank model, served through a hand-built ONNX graph that streams the original weights
- Limits written up front: the model was trained on another central bank, and words are not policy

`Hugging Face` `Transformers.js` `ONNX Runtime` `JavaScript`

#### [Ming Crisis Atlas](https://huggingface.co/datasets/Kukai-7/ming-crisis-atlas) · Historical data on Hugging Face

What brought down the Ming? 111,623 disaster events from Chinese local gazetteers, 1368 to 1644, each dated, mapped to one of 1,397 places and linked to its source, with El Niño and temperature reconstructions alongside.

- In 1640, 229 places record people eating one another; two thirds of all such places in the dynasty fall in its last eight years
- Annual panel built to separate weather from archive survival, with the limits written down
- No simple El Niño signal: a negative result, kept in the card

`Python` `Pandas` `Matplotlib` `Shapely` `Parquet`

#### [Edo Rice, Paper and Protest](https://huggingface.co/datasets/Kukai-7/edo-rice-paper-protest) · Historical data on Hugging Face

Did paper money and rice prices drive peasant revolts in Edo Japan? Fourteen rice price series, thirteen weather diaries read day by day, fifty notable uprisings and the domains that issued paper notes, 1620 to 1867, all on the map.

- Prices jump about 17% above trend in famine years, after cool and rainy summers
- The notable uprisings do not follow prices: thirty of fifty were about taxes, five about rice
- [Code](https://github.com/Kukai-7/edo-rice-paper-protest)

`Python` `Pandas` `Matplotlib` `Parquet`

#### [Silver Road: Potosí to Ming China](https://huggingface.co/datasets/Kukai-7/silver-road-potosi-ming) · Historical data on Hugging Face

Did American silver make, and then break, Ming China? The royal treasury of Potosí year by year, 1560 to 1823, the price of rice in silver in China, and the disasters of the late Ming, with the routes of the silver trade on a Pacific-centred map.

- Registered silver goes from about 30 to 180 tonnes a year in two decades, then declines slowly; it does not collapse before 1644
- Rice gets dearer in silver across the dynasty, and famine follows drought rather than silver
- [Code](https://github.com/Kukai-7/silver-road-potosi-ming)

`Python` `Pandas` `xlrd` `Matplotlib` `Parquet`

<p>
  <a href="https://huggingface.co/datasets/Kukai-7/ming-crisis-atlas"><img src="https://huggingface.co/datasets/Kukai-7/ming-crisis-atlas/resolve/main/assets/map_1637_1644.png" width="32%" alt="Ming Crisis Atlas" /></a>
  <a href="https://huggingface.co/datasets/Kukai-7/edo-rice-paper-protest"><img src="https://huggingface.co/datasets/Kukai-7/edo-rice-paper-protest/resolve/main/assets/map_edo.png" width="32%" alt="Edo Rice, Paper and Protest" /></a>
  <a href="https://huggingface.co/datasets/Kukai-7/silver-road-potosi-ming"><img src="https://huggingface.co/datasets/Kukai-7/silver-road-potosi-ming/resolve/main/assets/scatter_matrix.png" width="32%" alt="Silver Road" /></a>
</p>

#### [China under Deng](https://huggingface.co/datasets/Kukai-7/deng-era-china) · Macroeconomic data on Hugging Face

Money, growth and opening, 1978 to 1997: 21 World Bank series set against the two decades before and against India, Japan and the United States, with a map of the reform zones and a dated list of reforms. Limits stated up front: official statistics, a flattering baseline, two inflation series. [Code](https://github.com/Kukai-7/deng-era-china)

#### [France 1980 to 2026](https://huggingface.co/datasets/Kukai-7/france-economy-1980-2026) · Macroeconomic data on Hugging Face

Twenty-three governments next to debt, deficits, growth, unemployment, pensions and the nuclear fleet, from INSEE, Eurostat and the World Bank. Descriptive and non-partisan: governments are set next to the data, not scored. [Code](https://github.com/Kukai-7/france-economy-1980-2026)

`Python` `Pandas` `SDMX` `Matplotlib` `Parquet`

#### [Pharma Sales & P&L Dashboard](https://github.com/Kukai-7/pharma-sales-dashboard) · Power BI

A three-page report on a pharmaceutical distributor: executive P&L with waterfall, product performance, regional performance. Built on a star schema with a dedicated DAX measures table.

`Power BI` `Power Query` `DAX`

#### [Manufacturing Cost Analytics](https://github.com/Kukai-7/manufacturing-cost-analytics) · Easy Factory

Standard costing and purchasing analytics from the factory floor: BOM update automation in Python, purchasing price trends by material family, standard cost models, tooling analytics. Shown on **synthetic data**, originals stay under NDA.

`Python` `openpyxl` `Excel` `React`

---

### Side projects

| Project | What | |
|---|---|---|
| **東海道 · Tōkaidō, the Journey** | A cinematic walk along the Tōkaidō, from Edo to Naniwa, through Hiroshige's prints, on a map traced on Japan's real coastline | [Play](https://kukai-7.github.io/tokaido/) · [Code](https://github.com/Kukai-7/tokaido) · [Dataset](https://huggingface.co/datasets/Kukai-7/tokaido-53-stations) |
| **月百姿 · One Hundred Aspects of the Moon** | An online exhibition of Yoshitoshi's last great series: for each print, its story, its hero's voice and a darker counter-tale | [Open](https://kukai-7.github.io/hundred-aspects-of-the-moon/) · [Code](https://github.com/Kukai-7/hundred-aspects-of-the-moon) |
| **Ishibumi** | Location-based explorer of forgotten writers in Kyoto and Osaka | *Coming soon* |

<sub>Built in vanilla JavaScript, written in French. This is where my history side meets code.</sub>

---

### History, my other dataset

**Edo Japan**, the Genroku era above all: Osaka merchants, the floating world and the novels of Ihara Saikaku. **Song and Ming China**: paper money, maritime trade, porcelain and the long fall of the Ming. **Medieval travellers**: Marco Polo, William of Rubruck, John of Plano Carpini, John of Montecorvino, Ibn Battuta.

Questions I play with, turning historical sources into small datasets:

| Question | Data | Status |
|---|---|---|
| What brought down the Ming? | Famine, drought, banditry and climate shocks, county by county | [Dataset](https://huggingface.co/datasets/Kukai-7/ming-crisis-atlas) |
| Did paper money and rice prices drive peasant revolts in Edo Japan? | Uprisings, domain notes (*hansatsu*), rice famines | [Dataset](https://huggingface.co/datasets/Kukai-7/edo-rice-paper-protest) |
| Did American silver make, and then break, Ming China? | Potosí treasury accounts, rice prices in silver, late Ming disasters | [Dataset](https://huggingface.co/datasets/Kukai-7/silver-road-potosi-ming) |
| How busy were the great ports of the 13th century? | Ship counts at Calicut and Guangzhou from travellers' accounts and port records | Open question |

---

### Tools

`Python` `Pandas` `Jupyter` `Power BI` `Excel / VBA` `SQL` `R` `Bloomberg Terminal` `JavaScript` `Git` `Hugging Face` `Claude` `Cursor`

### Off the clock

Drawing · ukiyo-e prints, Hiroshige and Hokusai · books, in whatever language I can manage · Rome, the Punic Wars and Cicero · kendo and rock climbing

French (native) · English (fluent) · Spanish (fluent) · Mandarin (intermediate) · Japanese (beginner) · Latin

<sub>Fluent in Spanish, and yet I've probably spent more hours with Cicero. He never ordered tapas.</sub>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Noto+Serif+JP&weight=500&size=22&duration=3500&pause=1500&color=2F81F7&vCenter=true&width=620&height=40&lines=%E6%B8%A9%E6%95%85%E7%9F%A5%E6%96%B0;learn+the+new+by+revisiting+the+old" alt="温故知新 · learn the new by revisiting the old" /></a>
