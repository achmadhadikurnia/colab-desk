# 🖥️ ColabDesk

**ColabDesk** transforms Google Colab into a fully functional Virtual Desktop PC accessible directly from your web browser, without needing any local VNC viewer installations.

Built for simplicity and minimal user interaction.

## ✨ Features
- **One-Click Execution**: No confusing multi-step cells. Fill the form, click run, and you're done!
- **Direct Browser Access**: Powered by noVNC and XFCE4.
- **Smart Token Fallback**: Experiencing ngrok rate limits? Paste a list of multiple ngrok tokens, and the script will automatically shuffle and try them until a stable tunnel is created.
- **Automated Setup**: Installs desktop environment, browser (Google Chrome), and tunneling tools automatically.

## 🚀 How to Use
1. Upload the `ColabDesk.ipynb` file to your [Google Colab](https://colab.research.google.com/).
2. On the right-side form, configure your preferred **VNC Password** and **Resolution**.
3. In the **Ngrok Tokens** field, paste your token(s) from [ngrok.com](https://dashboard.ngrok.com). 
   *(You can paste a list of multiple tokens at once!)*
4. Click the **Play (Run cell)** button.
5. Wait ~2-3 minutes. A secure browser link will be generated. Click it, enter your password, and enjoy your cloud desktop!

## ☕ Support This Project
If you find this project useful, you can support me here:
- [Buy Me a Coffee](https://www.buymeacoffee.com/achmadhadikurnia)
- [Saweria](https://saweria.co/achmadhadikurnia)

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
