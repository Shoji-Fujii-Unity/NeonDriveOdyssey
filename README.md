# Neon Drive Odyssey

This README describes the game in supported languages.
Supported game languages are Japanese, English, and Spanish.

---

## 日本語

### タイトル
Neon Drive Odyssey  
ネオン・ドライブ・オデッセイ

### ゲーム概要
Neon Drive Odyssey は、Three.js を使用したブラウザ版 3D ドライブゲームです。  
PC とスマートフォンでプレイできます。

スマートフォンでは、横長画面でのプレイを推奨しています。  
横画面にすることで、より広い視点でゲーム画面を表示できます。

### 対応ブラウザ
- 最近の Google Chrome
- 最近の Microsoft Edge
- 最近の Firefox
- 最近の Safari
- WebView 対応ブラウザ

ゲーム実行には WebGL が必要です。  
Three.js を CDN から読み込んでいるため、初回はインターネット接続が必要です。

### 遊び方
1. index.html をブラウザで開きます。
2. タイトル画面でゲームスタートを押します。
3. ステージ一覧からステージを選びます。
4. 横長の画面で、ゴールまで走りましょう。

### ステージ
このゲームには、自動生成で長めのコースを持つステージが多数用意されています。  
ステージ数は 30 あり、ステージが進むほどコースが長く、難易度が高くなります。

ステージは、距離、道路幅、速度、カーブ、チェックポイント数によって徐々に難しくなります。  
コースの形状はステージ番号から再現可能に生成されます。

### 操作方法

#### PC
- W キー または 上矢印キー: アクセル
- S キー または 下矢印キー: ブレーキ
- A キー または 左矢印キー: 左ハンドル
- D キー または 右矢印キー: 右ハンドル
- スペースキー: ブレーキ
- R キー: レース場に戻る
- Esc キー: 一時停止

#### スマホ / タブレット
- 画面を横回転させてください。
- 左下の左右ボタンでハンドル操作ができます。
- 右下の GAS ボタンで加速できます。
- 右下の BRK ボタンで減速できます。

### サウンド
タイトル画面、ステージ選択画面、一時停止画面からサウンドを ON / OFF に切り替えることができます。

エンジン音、チェックポイント通過音、クリア音があります。

### 多言語対応
ゲーム本体は次の言語に対応しています。

- 日本語
- English
- Español

Language ボタンを押すと、次の言語に切り替わります。  
現在の言語設定は、ブラウザのローカルストレージに保存されます。

### セーブデータ
ゲームの進行データは、ブラウザのローカルストレージに保存されます。

保存される内容は次の通りです。

- 初期解除ステージ
- 各ステージのベストタイム
- 現在の言語設定
- サウンド ON / OFF 設定
- 進行中の状態

ブラウザのサイトデータ削除やブラウザ再起動で、セーブデータは削除されることがあります。

### 画面サイズについて
ゲームは横長画面でプレイすることを想定しています。  
縦長画面の場合は、横長に回転してくださいと案内されます。

スマートフォンでは、ゲーム画面の操作性を確保するため、横画面表示を強く推奨しています。

### 注意事項
- 端末性能により、フレームレートが低下する場合があります。
- 長時間プレイすると、端末が熱を持つことがあります。
- 自動生成ステージのため、同じステージ番号であれば同じコース形状になります。
- 本ゲームは WebGL 対応ブラウザでの動作を前提としています。

### ファイル構成
このゲームは次のファイルを想定しています。

- index.html: ゲーム本体の HTML ファイル
- README.md: この README

---

## English

### Title
Neon Drive Odyssey

### Overview
Neon Drive Odyssey is a browser-based 3D driving game made with Three.js.  
It can be played on PC and mobile devices.

The game is designed for landscape screens.  
Rotating your mobile device to landscape is recommended for better visibility and controls.

### Supported Browsers
- Recent Google Chrome
- Recent Microsoft Edge
- Recent Firefox
- Recent Safari
- WebGL-enabled browsers

Three.js is loaded from a CDN, so an internet connection is required for the first load.

### How to Play
1. Open index.html in a browser.
2. Press start on the title screen.
3. Select a stage from the stage list.
4. Drive to the goal in landscape mode.

### Stages
The game includes many generated long driving stages.  
There are 30 stages, and difficulty increases as you unlock later stages.

Stages become harder through longer routes, narrower roads, higher speed targets, sharper curves, and more checkpoints.  
Generated courses are reproducible from the stage number.

### Controls

#### PC
- W key or Up arrow: accelerate
- S key or Down arrow: brake
- A key or Left arrow: steer left
- D key or Right arrow: steer right
- Space key: brake
- R key: respawn
- Esc key: pause

#### Mobile / Tablet
- Rotate to landscape mode.
- Use the left and right buttons at the bottom-left to steer.
- Use the GAS button at the bottom-right to accelerate.
- Use the BRK button at the bottom-right to brake.

### Sound
Sound can be turned ON or OFF from the title screen, stage select screen, and pause screen.

There are engine sounds, checkpoint sounds, and a clear sound.

### Supported Languages
The game supports these languages:

- Japanese
- English
- Spanish

The Language button cycles through supported languages.  
The selected language is saved in the browser local storage.

### Save Data
Game progress is saved in the browser local storage.

Saved data includes:

- unlocked stages
- best times for each stage
- language setting
- sound setting
- progress state

Clearing site data or browser storage may remove saved data.

### Screen Orientation
This game is designed for landscape orientation.  
If the screen is vertical, the game will ask you to rotate your device.

Landscape mode is strongly recommended on mobile devices.

### Notes
- Frame rate may vary depending on device performance.
- Devices may become warm during long play sessions.
- Generated stages use stage-based seeds, so each stage reproduces the same route.
- The game requires a WebGL-capable browser.

### Files
This game assumes the following files:

- index.html: main HTML game file
- README.md: this README

---

## Español

### Título
Neon Drive Odyssey

### Resumen
Neon Drive Odyssey es un juego de conducción 3D para navegador creado con Three.js.  
Puede jugarse en PC y dispositivos móviles.

El juego está diseñado para pantallas en orientación horizontal.  
Se recomienda girar el móvil a modo apaisado para mejorar la visibilidad y los controles.

### Navegadores compatibles
- Google Chrome reciente
- Microsoft Edge reciente
- Firefox reciente
- Safari reciente
- Navegadores compatibles con WebGL

Three.js se carga desde una CDN, por lo que se requiere conexión a internet la primera vez que se abre el juego.

### Cómo jugar
1. Abrir index.html en el navegador.
2. Pulsar Start en la pantalla de título.
3. Elegir una etapa desde la lista de etapas.
4. Conducir hasta la meta en modo horizontal.

### Etapas
El juego incluye muchas etapas largas generadas automáticamente.  
Hay 30 etapas y la dificultad aumenta al avanzar.

Las etapas se vuelven más difíciles mediante rutas más largas, carreteras más estrechas, velocidades más altas, curvas más cerradas y más puntos de control.  
Las rutas se generan a partir del número de etapa y son reproducibles.

### Controles

#### PC
- Tecla W o flecha arriba: acelerar
- Tecla S o flecha abajo: frenar
- Tecla A o flecha izquierda: girar a la izquierda
- Tecla D o flecha derecha: girar a la derecha
- Barra espaciadora: frenar
- Tecla R: reaparecer
- Esc: pausa

#### Móvil / Tablet
- Girar el dispositivo a modo apaisado.
- Usar los botones de dirección abajo a la izquierda.
- Usar el botón GAS abajo a la derecha para acelerar.
- Usar el botón BRK abajo a la derecha para frenar.

### Sonido
El sonido puede activarse o desactivarse desde la pantalla de título, selección de etapa y pausa.

Hay sonidos de motor, paso por checkpoint y final de etapa.

### Idiomas compatibles
El juego admite estos idiomas:

- Japonés
- Inglés
- Español

El botón Language cambia entre idiomas.  
El idioma seleccionado se guarda en el almacenamiento local del navegador.

### Datos guardados
El progreso se guarda en el almacenamiento local del navegador.

Los datos guardados incluyen:

- etapas desbloqueadas
- mejores tiempos de cada etapa
- idioma seleccionado
- estado de sonido
- progreso

Borrar datos del sitio o almacenamiento del navegador puede eliminar los datos guardados.

### Orientación de pantalla
Este juego está diseñado para pantalla horizontal.  
Si la pantalla está vertical, el juego pedirá girar el dispositivo.

Se recomienda encarecidamente el modo apaisado en dispositivos móviles.

### Notas
- La tasa de fotogramas puede variar según el rendimiento del dispositivo.
- El dispositivo puede calentarse tras jugar durante mucho tiempo.
- Las etapas generadas usan el número de etapa, por lo que cada etapa reproduce la misma ruta.
- El juego requiere un navegador compatible con WebGL.

### Archivos
Este juego espera los siguientes archivos:

- index.html: archivo principal del juego
- README.md: este README