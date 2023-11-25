<div align="center">
<h1 align="center">ImgPilot</h1>

Image pilot with the power of Real-Time Latent Consistency Model.
<br/>
<br/>


[preview.webm](https://github.com/leptonai/imgpilot/assets/1506722/673ffa1b-e680-4f69-b219-31b5265e1cb4)



[DEMO](https://imgpilot.com/)
</div>

## ✨ Features

- Includes complete front-end and back-end code.
- Support deployment both locally and in the cloud.
- Fully based on open source and can be used for commercial purposes.


## 📦 Install

```bash
# Install web dependencies
npm install

# Install server dependencies
pip install -r photon/lcm_dreamshaper/requirements.txt -U
```

## ⌨️ Development

```bash
# Start server on localhost:8080

lep photon run -n imgpilot -m photon/lcm_dreamshaper/main.py --local
```

```bash
# Start web server on localhost:3000

npm run dev
```



## 🔗 Built with

- [Lepton AI](https://github.com/leptonai/leptonai)
- [Excalidraw](https://github.com/excalidraw/excalidraw)
- [Real-Time-Latent-Consistency-Model](https://huggingface.co/spaces/radames/Real-Time-Latent-Consistency-Model)
