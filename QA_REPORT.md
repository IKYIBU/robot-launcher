# v23 自動検証結果（2026-11-12）

実施方法：Linux headless Chromium / Playwright、HTMLを直接読み込んでテスト（実公開URLへの反映テストではない）。

```json
{
  "320": {
    "title": "ROBOT LAUNCHER v23 | 無料ブラウザゲーム",
    "bodyWidth": 320,
    "winWidth": 320,
    "gameVisible": true,
    "links": [
      "about.html",
      "privacy.html",
      "contact.html"
    ],
    "adScripts": 0,
    "privacyDialog": true,
    "privacyLink": 1,
    "gameVisibleAfterStart": true,
    "errors": []
  },
  "390": {
    "title": "ROBOT LAUNCHER v23 | 無料ブラウザゲーム",
    "bodyWidth": 390,
    "winWidth": 390,
    "gameVisible": true,
    "links": [
      "about.html",
      "privacy.html",
      "contact.html"
    ],
    "adScripts": 0,
    "privacyDialog": true,
    "privacyLink": 1,
    "gameVisibleAfterStart": true,
    "errors": []
  },
  "768": {
    "title": "ROBOT LAUNCHER v23 | 無料ブラウザゲーム",
    "bodyWidth": 768,
    "winWidth": 768,
    "gameVisible": true,
    "links": [
      "about.html",
      "privacy.html",
      "contact.html"
    ],
    "adScripts": 0,
    "privacyDialog": true,
    "privacyLink": 1,
    "gameVisibleAfterStart": true,
    "errors": []
  },
  "1280": {
    "title": "ROBOT LAUNCHER v23 | 無料ブラウザゲーム",
    "bodyWidth": 1280,
    "winWidth": 1280,
    "gameVisible": true,
    "links": [
      "about.html",
      "privacy.html",
      "contact.html"
    ],
    "adScripts": 0,
    "privacyDialog": true,
    "privacyLink": 1,
    "gameVisibleAfterStart": true,
    "errors": []
  },
  "about.html": {
    "heading": "ゲーム紹介",
    "navLinks": 4,
    "horizontalOverflow": false,
    "errors": []
  },
  "contact.html": {
    "heading": "お問い合わせ",
    "navLinks": 4,
    "horizontalOverflow": false,
    "errors": []
  },
  "privacy.html": {
    "heading": "プライバシー・データの取扱い",
    "navLinks": 4,
    "horizontalOverflow": false,
    "errors": []
  }
}
```

### 制約
- ブラウザの実際のGitHub Pages配信・iPhone Safari・Android実機は今回未検証。
- ゲーム全6ステージの攻略確認はv21で行われ、v23では再試験していない。
- 個人情報を扱う非公開窓口とGitHub Issues有効性は未確認。
- 広告タグは追加していないため広告審査・配信・収益は未検証。
