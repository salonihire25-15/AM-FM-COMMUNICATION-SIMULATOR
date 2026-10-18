# AM/FM Communication Simulator Website

## Run locally
1. Keep `index.html` and this README in the same folder.
2. Double-click `index.html` to open it in Chrome or Edge.
3. Internet is required for Chart.js and Google Fonts loaded from CDNs.

## Publish online free with GitHub Pages
1. Sign in at https://github.com/ and create a **public** repository, for example `am-fm-communication-simulator`.
2. Upload `index.html` to the repository root (you can also upload this README).
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then click **Save**.
6. Wait for GitHub Pages to publish the site. The URL will look like `https://YOUR-USERNAME.github.io/am-fm-communication-simulator/`.

## Included features
- AM/FM mode selection
- Adjustable message frequency, carrier frequency and channel noise
- Message, carrier, modulated, noisy received and recovered signal charts
- FFT magnitude spectra
- SNR based on modulated-signal power divided by added-noise power
- Theory notes and key project parameters

## Scientific notes
This is a browser-based JavaScript implementation, not an execution of the Scilab code. Defaults are Fs = 100 kHz, duration = 5 ms, fm = 1 kHz, fc = 10 kHz, AM index μ = 0.5, and FM index β = 2. SNR is calculated from modulated-signal power divided by added-noise power; it is not recovered-message SNR. The demodulators are educational approximations, particularly at high noise levels, so compare the plots with your Scilab results before submission.
