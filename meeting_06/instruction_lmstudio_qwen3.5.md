# How to Download, Install LM Studio, and Search for the Qwen3.5-0.8B Model

## What is LM Studio?

LM Studio is a free desktop application that lets you run large language models (LLMs) locally and privately on your own computer. It provides a chat interface and a programmable API, so you can experiment with AI models without sending data to the cloud.

Website: [https://lmstudio.ai](https://lmstudio.ai)

---

## Part 1: Download LM Studio

1. Open your web browser and go to **[https://lmstudio.ai](https://lmstudio.ai)**.

2. On the homepage, you will see a large **Download** button in the center of the page. The site automatically detects your operating system (macOS, Windows, or Linux).

3. Alternatively, click the **Download** button in the top-right corner of the navigation bar, or go directly to **[https://lmstudio.ai/download](https://lmstudio.ai/download)**.

4. On the download page, you can select your specific configuration:
   - **Operating System**: macOS, Windows, or Linux
   - **Architecture**: M series (Apple Silicon) for Mac; x64 or ARM for Windows/Linux
   - **Version**: The latest stable version (currently **0.4.6**) is selected by default

> **⚠️ Important Note for macOS Users:**
> Most Mac students will have **Apple Silicon** (M1, M2, M3, M4 chips). This is the supported version — go ahead and download it.
>
> However, if you have an **older Intel-based Mac**, please **do NOT download LM Studio** — there is no Intel macOS version available. To check your chip, click the **Apple menu () > About This Mac**. If it says "Chip: Apple M1/M2/M3/M4", you are good to go. If it says "Processor: Intel", LM Studio will not work on your machine.

5. Click the green **"Download for [your OS]"** button to start downloading the installer.

---

## Part 2: Install LM Studio

### For macOS (Apple Silicon Only — M1/M2/M3/M4)

> **Intel Mac users: LM Studio does not support Intel Macs. Please do not attempt to install it.**

1. Once the `.dmg` file has finished downloading, double-click it to open the disk image.
2. Drag the **LM Studio** icon into the **Applications** folder.
3. Open **LM Studio** from your Applications folder.
4. If macOS displays a security warning (because the app was downloaded from the internet), go to **System Settings > Privacy & Security** and click **"Open Anyway"**.

### For Windows

1. Once the `.exe` installer has finished downloading, double-click it to run.
2. Follow the on-screen installation prompts (accept the license agreement, choose an install location, etc.).
3. After installation completes, launch **LM Studio** from the Start menu or desktop shortcut.

### For Linux

1. Download the `.AppImage` file from the download page.
2. Make it executable by running in your terminal:
   ```bash
   chmod +x LM-Studio-*.AppImage
   ```
3. Run the AppImage:
   ```bash
   ./LM-Studio-*.AppImage
   ```

---

## Part 3: Search for the Qwen3.5-0.8B Model

Once LM Studio is installed and open, follow these steps to find and download the **Qwen3.5-0.8B** model:

1. **Open LM Studio** on your computer.

2. Look at the **left sidebar**. You will see several icons. Click the **magnifying glass icon** (Search / Discover) to open the model search page.

3. In the **search bar** at the top of the Discover page, type:

   ```
   Qwen3.5-0.8B
   ```

4. The search results will show available versions of the Qwen3.5 0.8B model. You may see different quantized formats (e.g., Q4_K_M, Q8_0, etc.). Smaller quantizations use less RAM but have slightly lower quality.

5. **Choose a version** that fits your hardware:
   - **Q4_K_M** — Good balance of quality and size (recommended for most users)
   - **Q8_0** — Higher quality, requires more RAM
   - **F16** — Full precision, requires the most RAM

6. Click the **Download** button next to your chosen version. The model will begin downloading. File sizes vary depending on quantization, but the 0.8B model is relatively small (typically under 1 GB).

7. Once the download is complete, you can **load the model** by clicking on it or selecting it from the model dropdown at the top of the chat interface.

8. Start chatting with the model in the **Chat** tab!

---

## Tips

- **Check your RAM**: Even though Qwen3.5-0.8B is a small model, make sure you have at least 2-4 GB of free RAM for a smooth experience.
- **GPU acceleration**: If you have a compatible GPU (NVIDIA with CUDA, Apple Silicon, or AMD on some systems), LM Studio will automatically use it for faster inference.
- **Explore more models**: The Discover page in LM Studio has thousands of models. You can also browse the online catalog at [https://lmstudio.ai/models](https://lmstudio.ai/models).

---

*Document created on March 3, 2026*
