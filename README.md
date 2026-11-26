# Eight Months of Us (Visual Studio Code Edition)

Pure HTML, CSS, and JavaScript version — hindi kailangan ng `npm install` o build tools. Gumagana agad sa Visual Studio Code!

## Paano I-run sa Visual Studio Code

1. I-unzip ang `eight-months-of-us.zip` sa computer mo.
2. Buksan ang buong folder sa **Visual Studio Code** (`File -> Open Folder...`).
3. I-install ang **Live Server** extension (`ritwickdey.LiveServer`) kung wala pa.
4. I-right click ang `index.html` at piliin ang **Open with Live Server** (o i-click ang **Go Live** sa ibaba ng VS Code).
5. Magbubukas ito agad sa `http://127.0.0.1:5500/index.html`.

## Paano Maglagay ng MP3 Song

- **Paraan 1 (Sa folder):** Ilagay ang `.mp3` file mo sa loob ng `assets/music/` at pangalanan itong **`kay-tagal-kitang-hinintay.mp3`** (`assets/music/kay-tagal-kitang-hinintay.mp3`).
- **Paraan 2 (Sa loob ng website):** Buksan ang Creator Mode at i-click ang **Upload MP3 File**.

## Paano I-edit ang Love Letter at Creator PIN

- Buksan ang `index.html` sa VS Code at i-edit ang `window.MONTHSARY_CONFIG` (nandiyan ang `letterSalutation`, `letterParagraphs`, `letterSignOff`, `partnerName`, `senderName`, `creatorPin`, at `notificationEmail`).
- Para i-unlock ang **Creator Mode** (ikaw lang ang makakakita ng edit/upload buttons):
  - I-**triple click** ang `"Eight Months of Us"` sa header o pindutin ang **`Ctrl + Shift + E`**.
  - Default PIN: **`0407`**
