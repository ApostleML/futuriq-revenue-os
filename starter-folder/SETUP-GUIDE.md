# Setup Guide (Windows, one page)

You don't need to code. You'll type a few short commands into a window called PowerShell. Copy each command from this page exactly as written.

## What you need first
- A Windows computer and an internet connection.
- A paid Claude plan (Pro or Max). A free account won't work.

## Steps
1. **Open PowerShell.** Click the Start button, type `PowerShell`, and click **Windows PowerShell**. A blue or black window opens. This is where you type.
2. **Install Claude Code.** Copy this line, right-click inside PowerShell to paste it, and press Enter:
   `irm https://claude.ai/install.ps1 | iex`
   Wait until it says it's finished.
3. **If it asks for Git for Windows,** go to **git-scm.com**, click **Download for Windows**, run the file, and click **Next** on every screen, keeping the default choices. Then run step 2 again.
4. **Close PowerShell and open it again** (step 1). Windows only notices the new install in a fresh window.
5. **Download the starter folder.** Click the download link from the video or email. Find the ZIP file in your **Downloads** folder, right-click it, choose **Extract All**, then click **Extract**.
6. **Go to the folder.** Open the extracted folder in File Explorer. Windows often puts a folder inside a folder with the same name, so you'll see `revenue-chain-starter-folder` inside another `revenue-chain-starter-folder`. Open the inner one, the one that contains `business-brief.md`. Click the address bar at the top, copy the path, then type `cd`, a space, and paste the path **inside quotes**:
   `cd "C:\Users\YourName\Downloads\revenue-chain-starter-folder\revenue-chain-starter-folder"`
   Press Enter.
7. **Fill in your brief.** In File Explorer, right-click `business-brief.md`, choose **Open with**, then **Notepad**. Leave Section A alone; it is the example from the video. Fill in the section marked **YOUR IDEA**, then save. The chain reads only that section and stops if it is empty.
8. **Start Claude Code.** In PowerShell type `claude` and press Enter.
9. **Sign in.** When it asks how to log in, choose option **1** (your Claude account). Your browser opens. Sign in and click **Authorize**. If the browser shows a code, paste it back into PowerShell.
10. **Trust the folder.** When Claude Code asks whether you trust the files in this folder, choose **Yes**.
11. **Run it.** Paste this and press Enter:
    `Run the Revenue Agent runbook on business-brief.md`
    The four agents now run one after another. The main Claude Code session coordinates them, and it also saves the first agent's report, because that agent can't save files itself. Your results appear in the `outputs` folder.

## If something goes wrong
- **"Cannot find path" or "path not found":** the folder path is wrong. To find the right one, paste this into PowerShell, and press Enter. It may print two lines. Use the longer one, the path that ends with the name twice, in step 6:
  `Get-ChildItem $HOME -Recurse -Directory -Filter "revenue-chain-starter-folder" -ErrorAction SilentlyContinue | Select-Object FullName`
- **"claude is not recognized":** close PowerShell, open a new window (step 4), and go to your folder again (step 6).
- **Stay safe:** never paste a password or code anywhere except where Claude Code or the official Claude sign-in page asks for it. Nobody from FuturIQ will ever ask you for one.
- **Still stuck?** Reply to the starter-folder email and say which step number stopped you.
