---
layout: wiki
title: "Installation for Windows"
lang: "en"
permalink: "/wiki/Installation-for-Windows"
---

{% include breadcrumb.html root="Using Jamulus" branch1="Getting Started" branch1-url="Getting-Started" %}

# Windows Setup (Guide)

## Requirements

- **ASIO Driver** (If you have a sound card/interface, use its native ASIO driver. If you don't have an sound card/interface, you should download and install [ASIO4ALL](https://www.asio4all.org){: target="_blank" rel="noopener noreferrer"} or an equivalent ASIO driver.)


## Installation
1. **Download Jamulus**: You can download Jamulus from 
[our official site]({{ site.download_root_link }}{{ site.download_file_names.windows }}){:target="blank" rel="noopener noreferrer"} or alternatively, from [SourceForge](https://sourceforge.net/projects/llcon/files/latest/download){:target="blank" rel="noopener noreferrer"}.
1. **Install Jamulus**: Double click the installer to launch it. If you get a warning notice from SmartScreen, click on "More info" and "Run anyway" to install Jamulus. (If you grabbed a new version of Jamulus and are one of the first people who downloaded it, Jamulus won't be whitelisted by SmartScreen yet. We don't pay for code signing.)



## Audio Setup

<div>
<button type="button" class="collapsible"><strong>Setting up audio with a native ASIO driver</strong>
<div></div></button>
<div class="content">
<ol>
<li>Make sure your interfaces, instruments/mics and headphones are plugged into your computer.</li>

<li>Close all other programs.</li>

<li>Run Jamulus and click on the <i>Settings</i> panel.</li>

<li>Select your device under the <i>Device</i> heading. Then, select your inputs and outputs under <i>Input Channel Mapping</i> and <i>Output Channel Mapping.</i></li>
</ol>
</div>
</div>

<div>
<button type="button" class="collapsible"><strong>Setting up audio with ASIO4ALL</strong>
<div></div></button>
<div class="content">
<p>
<ol>

<li>Make sure your desired interfaces and/or instruments are plugged into your computer.</li>

<li>Close all other programs.</li>

<li>Run Jamulus and click on the <i>Settings</i> panel.</li>

<li>Click on <i>ASIO Device Setup</i>. This will open the ASIO4ALL setup window.</li>

<li>Click on the wrench icon on the bottom right to enable advanced view.</li>

<li>Enable only the soundcard you want to use by clicking on the power button to the left. To see its inputs and outputs, click on the plus button and enable your inputs and outputs by clicking the power button next to its name.</li>

<li>Go back to your Jamulus settings, and select your inputs and outputs under <i>Input Channel Mapping</i> and <i>Output Channel Mapping</i>.</li>

<li>To check if your audio is working correctly, connect to a server to hear your instrument or voice.</li>
</ol>

<i>If you have difficulty finding your internal sound cards, they are commonly named Realtek High Definition Audio, Conexant or similar.</i>

</p>
</div>
</div>


*Concerning the inputs/outputs: Headphones and speakers are often labelled as output and microphones as inputs or capture.*

### Having trouble setting up ASIO4ALL?

If nothing works, first restart Jamulus and/or your PC to close background processes that may be accessing your sound card.

Afterwards, *set up the inputs/outputs again*. Enabled and accessible input/outputs show as lit up power buttons and play buttons. If instead you see a red cross or yellow symbol, close other applications that may be accessing your sound card (e.g. browser, Zoom, etc).

Have a look at [this video](https://youtu.be/_GzOsitVgLI) by [trombonepizza](https://github.com/trombonepizza) which gives more detailed setup information on ASIO4ALL.

Official and further information about how to configure ASIO4ALL is documented in the official [ASIO4ALL FAQs on the ASIO4ALL website](https://www.asio4all.org/index.php/help/faq/){: target="_blank" rel="noopener noreferrer"} and in the ASIO4ALL manual which can be found on your desktop or in the folder where the ASIO4ALL binary is installed (usually `C:\Program Files (x86)\ASIO4ALL v2\`)).

## All installed?

Jamulus has been installed and can be used now. You can now take a look at the

[Jamulus Onboarding page](Onboarding){: .button}
