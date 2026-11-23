# 画像生成プロンプト（Gemini 用）

生成した画像は、このフォルダ（`images/`）に下の「ファイル名」で保存してください。アプリに組みこみます。

## 共通のスタイル（すべてのプロンプトの最後に付ける）
```
Style: soft watercolor and gouache illustration for a middle-school music textbook, warm spring palette (cherry pink, fresh green, sky blue, warm cream), gentle light, clean composition, no text, no letters, no logos, no watermark.
```

## A. 見た目を大きく変える（優先）
| ファイル名 | 比率 | 使う場所 |
|---|---|---|
| hero.png | 16:9 | トップ画面 |
| scene-theme.png / scene-birds.png / scene-stream.png / scene-storm.png / scene-solo.png | 16:9 | 情景アニメーションの背景 |
| tip-echo.png など7枚 | 1:1 | 鑑賞のコツのカード |

## B. 足りない絵を補う
| ファイル名 | 比率 | 使う場所 |
|---|---|---|
| concerto.png | 4:3 | 協奏曲の演奏（写真がなかった枠） |
| pieta.png | 4:3 | バロック時代：ピエタ慈善院 |

## C. 仕上げ
| ファイル名 | 比率 | 使う場所 |
|---|---|---|
| og-image.png | 1200×630 | リンクを共有したときの画像 |
| sheet-header.png | 4:1 | ワークシートの見出し（白黒） |
| badge.png | 1:1 | 4ステップ完了のごほうび |

プロンプト本文はチャットで渡したものと同じです（下に再掲）。

## 組みこみ済み
- pieta.jpg（バロック時代のページと写真タブ。イメージイラストと表示）、scene-solo.jpg（独奏の見せ場の背景）、tip-echo・tip-kage（コツの絵）、sheet-header.png（ワークシート印刷の飾り）
- tip-kakeai（かけ合い）も入れた（エンドピン・あご当てあり）。作り直し候補：tip-kakeai、：concerto（エンドピン）
- concerto.jpg（写真タブ・協奏曲ページ。「イメージイラスト」と表示）、badge.jpg（まとめの完了バッジ）、og-image.jpg（リポジトリ直下。タイトル文字を重ねた）
- hero.jpg、scene-theme.jpg、scene-birds.jpg、scene-stream.jpg、scene-storm.jpg（幅1600pxに縮小して保存）
- tip-okaeri、tip-atsumi（上のにじみを切り取り）、tip-oto_e、tip-ugoki（余白を切りそろえて512pxの正方形に）
- まだ：scene-solo（いまは主題の絵に夕日の色を重ねて代用）、tip-echo・tip-kage・tip-kakeai（いまは絵文字）、concerto、pieta、og-image、sheet-header、badge

---
## プロンプト本文

### hero.png（16:9）
A wide spring landscape inspired by Vivaldi's "Spring": a flowering meadow with cherry blossoms, small songbirds flying, a clear stream, and in the far distance the silhouette of 18th-century Venice with a bell tower. In the foreground, a baroque violin and bow resting on the grass, with pink petals drifting in the air. Leave calm open sky on the left third for a title.

### scene-theme.png（16:9）
Spring has arrived: a bright sunny meadow full of flowers, gentle rolling green hills, cherry trees in bloom, a joyful festive mood. Wide view, nothing in the lower quarter but simple grass (captions will be placed there). No people, no animals.

### scene-birds.png（16:9）
A sunny spring morning in a blossoming orchard; several small colorful songbirds singing on branches, light airy atmosphere, lots of soft sky. Lower quarter simple grass. No people.

### scene-stream.png（16:9）
A clear spring stream flowing gently through a meadow, soft breeze moving the grass and willow branches, sparkling water, calm and peaceful mood. Lower quarter simple. No people.

### scene-storm.png（16:9）
The same spring meadow under a sudden thunderstorm: dark purple-grey clouds, a bright lightning bolt in the distance, rain sweeping across the hills, dramatic but not frightening for children. Lower quarter simple dark grass. No people.

### scene-solo.png（16:9）
After the storm: the sky clearing to a warm golden sunset over the meadow, a soft spotlight-like beam of sunlight on a single flowering tree in the center, puddles reflecting the light. Lower quarter simple. No people.

### 鑑賞のコツ（1:1・7枚。すべてに追加："simple icon-like illustration on a plain cream background, centered, generous margin"）
- tip-echo.png：Two friendly hills calling to each other: a large bold sound wave from the left hill and a smaller, softer echo wave answering from the right hill.
- tip-okaeri.png：A cherry blossom flower returning home along a circular path, like a loop arrow made of petals, warm and welcoming.
- tip-atsumi.png：Two stacks of musical sound layers side by side: a thick, rich stack of many colorful layers and a thin, light stack of just two pale layers.
- tip-oto_e.png：A violin bow painting a picture in the air: a small bird, wavy water lines and a lightning bolt appearing from the stroke of the bow.
- tip-ugoki.png：A child's fingertip drawing a flowing wavy line in the air that turns into a gentle stream.
- tip-kage.png：The same flower shown twice: on the left in bright sunlight, on the right under a soft passing cloud shadow, slightly muted colors.
- tip-kakeai.png：A single violin and a small group of string instruments facing each other with speech-bubble shapes (empty, no text) floating between them, like a friendly conversation.

### concerto.png（4:3）
A baroque chamber orchestra performing a violin concerto in an 18th-century Venetian hall with tall arched windows: a soloist violinist standing in front, behind them a small string ensemble (violins, violas, cellos without endpins, one double bass) and a harpsichord with its lid open; musicians in 18th-century coats and white wigs. Instruments drawn accurately: violins with four strings and f-holes, held on the left shoulder.

### pieta.png（4:3）
The Ospedale della Pietà in 18th-century Venice: girls in simple white dresses playing violins and cellos in a church gallery behind a decorative iron grille, candlelight, viewed from the church below. Gentle, respectful mood.

### og-image.png（1200×630）
A cheerful banner: a baroque violin surrounded by cherry blossoms, small songbirds, flowing music-staff ribbons and a tiny lightning bolt, on a soft spring gradient. Leave the right half calm for a title.

### sheet-header.png（4:1・白黒）
A horizontal decorative border for a printable worksheet: black line art only, white background, cherry blossoms, small birds, a violin and a flowing music staff ribbon. Suitable for photocopying.

### badge.png（1:1）
A round award badge: a golden laurel wreath around a violin and a cherry blossom, small stars, celebratory but simple.
