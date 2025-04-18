# AI Cloning Voice Free
Free voice cloning using Colab.

## Getting Started

Follow these steps to set up your free AI voice cloning:

1. **Open Colab** and run the following commands:

    ```bash
    # Check CUDA version
    !nvcc --version

    # Install PyTorch
    pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
    ```

2. **Install F5-TTS**:

    ```bash
    !pip install git+https://github.com/SWivid/F5-TTS.git
    from IPython.display import clear_output
    clear_output()
    ```

3. **Run F5-TTS with Gradio**:

    ```bash
    !f5-tts_infer-gradio --share
    ```
4. **Click the publick url **

Congratulations! You now have a lifetime of free AI voice cloning.

For eazy way, check out this [YouTube video](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbkVLLU1HbzVCUzdkeEZBVVB5ZE1ObTc4NC15QXxBQ3Jtc0ttVEFNT0tQTHpnc2xkVmNNd2lLam41eGpBYlBycUNGRWRpVDNiS1pWZENZSm82ODZEZDdiOUR1TUIxR1ZSTG5KWURDX19tMGZzZ3NrTHMxa1A4UWVvUHlIUTI0N1RyQlRaMGR0cldWRE5BdTNlaExRQQ&q=https%3A%2F%2Fcolab.research.google.com%2Fgithub%2FNeuralFalconYT%2FF5-TTS-Demo%2Fblob%2Fmain%2FF5_TTS_Latest.ipynb&v=VwWjg5FKah8).

5. **Click inspect, go to console **
💡 Copy and Paste (JavaScript):
```bash
function KeepColabAlive() {  
    setInterval(function() { console.log("Keeping Colab alive..."); }, 30000);  
}  
KeepColabAlive();
 ```
========================================================
⚠️ If you get a warning while pasting the code in the console, just type:
allow pasting and press Enter, then paste the JavaScript code again!
========================================================
⚠️ This method works for inactivity timeouts but only up to 12 hours because it's a free version of Colab. If you need longer runtimes:
Upgrade to Colab Pro/Pro+
Use Google Cloud/AWS for uninterrupted runs.
Run locally on your computer.
