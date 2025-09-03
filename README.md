<h1 align="center">舒適的 YAML 配置檔案</h1>
<p align="center">
  <i>我為自己維護自用的配置檔案。簡單清晰。</i>
  <br/><br/>
  <img width="210" alt="YAML" src="asset/logo.png"/>
  <br/><br/>
  <b><a href="https://wiki.metacubex.one/config/">虛空終端</a></b> | <b><a href="https://github.com/MetaCubeX/meta-rules-dat/tree/meta">MetaCubeX 規則</a></b> | <b><a href="https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash">blackmatrix7 規則</a></b>
  <br/><br/>
  <a target="_blank" href="https://github.com/Gholts/yaml"><img src="https://img.shields.io/github/last-commit/Gholts/yaml?logo=github&color=395799&logoColor=fff" alt="Last commit"/></a>
  <a href="https://github.com/Gholts/yaml/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-395799?logo=opensourceinitiative&logoColor=fff" alt="License CC BY-NC-SA 4.0"/></a>
</p>

* [Getting started](#-getting-started)
* [Acknowledgements](#-acknowledgements)
* [License](#-license)

## 🚀 Getting started

1. 選擇你的配置檔案
    - mihomo
        - `mihomo-router.yaml`
    - loon
        - 進階 - `loon.conf` (適合有軟路由的場景。替換 `loon.conf` 檔案內的所有 `replaceSSID` 為你的 ssid。替換 `replacerouterip` 為你的路由器後臺地址，如果為旁路由結構，填寫設備實際局域網 DNS 地址。同時還預留了 WireGuard 節點位置，如需替換為自己的地址即可，語法參考[官方文檔](https://nsloon.app/LoonManual/#/cn/node?id=%e8%8a%82%e7%82%b9%e6%a0%bc%e5%bc%8f)。 連線到你指定的 SSID 後，所有流量皆直連，由軟路由路由管理。)
    - stash (自 2025-Sep-2 不再維護)
        - 進階 - `ssid-stash`（適合有軟路由的場景。替換 `ssid-stash.yaml` 檔案內的所有 `replaceSSID` 為你的 SSID。連線到你指定的 SSID 後，所有流量皆直連，由軟路由路由管理。）
        - 普通 - `stash`（適合沒有軟路由，終端代理的場景。）

2. 把配置檔案中的**機場連結**或**節點資訊**替換為你的。

3. 如果需要客製化配置檔案中的內容，請參考 [虛空終端](https://wiki.metacubex.one/config/) 或 [Stash Wiki](https://stash.wiki/) 使其為正確的格式。

## 🏆 Acknowledgements

- [Mihomo](https://github.com/MetaCubeX/mihomo/) —— 所有的起點。
- [Sukkaw](https://github.com/SukkaW/Surge) —— 非常實用的規則。
- [Kelee](https://t.me/iKeLee) —— 我的配置文件基於 Kelee 的進階配置修改，感謝配置文件的提供和 Loon 插件規則的維護。
- [Qure](https://github.com/Koolson/Qure) —— 十分好看的資源圖標。
- [Zashboard](https://github.com/Zephyruso/zashboard) —— 好看好用的面板。
- [ChatGPT](https://chatgpt.com) —— 十分好的圖片生成。
- [七尺宇的 YAML 檔案梳理](https://youtu.be/watch?v=eUqf3lOhFSw) —— 我是從這裡開始的。

以上致謝不分先後。

## 📄 License

[CC BY-NC-SA 4.0 license](LICENSE).
