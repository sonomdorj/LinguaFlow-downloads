# LinguaFlow: test downloads

LinguaFlow translates documents into Mongolian with AI, checks its own work, and learns from your proofreader's corrections. It runs on your own computer, and your files stay there.

**This is a test build.** Thank you for trying it! Please tell us what works and what doesn't (see [Feedback](#feedback)).

## 1. Download

Open the **[latest release](../../releases/latest)** and pick the file for your computer:

| Your computer | Download |
|---|---|
| Mac with an Apple chip (M1, M2, M3, M4…) | `LinguaFlow-…-mac-apple-silicon.dmg` |
| Mac with an Intel chip | `LinguaFlow-…-mac-intel.dmg` |
| Windows 10 or 11 | `LinguaFlow-Setup-….exe` |

Not sure which Mac you have? Click the Apple menu → **About This Mac**, then look at **Chip** (Apple) or **Processor** (Intel).

## 2. Install

### Mac
1. Open the downloaded `.dmg`.
2. Drag **LinguaFlow** onto the **Applications** folder.
3. Open **Applications** and double-click **LinguaFlow**.
4. **The first time only,** macOS says it can't check the app for malicious software. This test build isn't signed with an Apple certificate yet. To open it anyway:
   - Click **Done** (or **OK**).
   - Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to "LinguaFlow was blocked".
   - Confirm with **Open Anyway** and your Mac password.
5. A browser tab opens with LinguaFlow. **The first start can take up to 20 seconds.**

### Windows
1. Double-click `LinguaFlow-Setup-….exe`.
2. **The first time only,** Windows may say "Windows protected your PC". This test build isn't signed yet. Click **More info**, then **Run anyway**.
3. Click through the installer. It doesn't need an administrator.
4. LinguaFlow opens a browser tab and a small window that says "LinguaFlow is running". **Keep that small window open while you work.**

## 3. First start: connect the AI

LinguaFlow uses OpenAI to translate, so you need **your own OpenAI API key**:
1. Create a key at [platform.openai.com/api-keys](https://platform.openai.com/api-keys) and add a little credit to your OpenAI account.
2. In LinguaFlow, click **Settings**, paste the key into **API key**, and press **Save connection**.

Your key stays on your computer. Translating a few chapters usually costs well under $1, and every run shows its price before it starts.

## 4. Use it

Click **Help** in LinguaFlow's menu for a step-by-step guide: Start → Translate → Progress → download → Learn.

- **Your files** are saved in **Documents → LinguaFlow** (Settings shows the exact place).
- **Open it again:** Mac: Applications → LinguaFlow. Windows: Start menu → LinguaFlow. If it's already running, this just opens the browser tab.
- **Stop it:** Settings → **Quit LinguaFlow**. On Windows you can also close the small LinguaFlow window.

## Updating

Download the new version and install it the same way, over the old one. Your files in **Documents → LinguaFlow** are kept.

## Feedback

In LinguaFlow, click **Settings → Send feedback** (or the link at the top of **Help**). It opens an email with the version number filled in. Please tell us:
- what you were trying to do;
- what happened instead (a screenshot helps);
- for an error, the last lines of the **Progress** page.

## Good to know (test build)
- Scans and photos can't be read yet. Use Word (.docx), PDF with selectable text, or .txt files.
- On Windows, proofread files must be **.docx** (not the old .doc).
- Uninstalling never deletes your files in Documents → LinguaFlow.
