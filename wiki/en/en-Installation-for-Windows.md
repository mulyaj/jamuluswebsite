---
layout: wiki
title: "Installation for Windows"
lang: "en"
permalink: "/wiki/Installation-for-Windows"
---

{% include breadcrumb.html root="Setting Up Jamulus" branch1="Windows" %}

# Windows Setup (Guide)

## Requirements

- **ASIO Driver** (If you have a sound card/interface, use its native ASIO driver. If you don't have an sound card/interface, you should download a generic driver like ASIO4ALL or an equivalent ASIO driver.)

    [ASIO4ALL v2.14 Download](https://github.com/jamulussoftware/assets/raw/main/ASIO4ALL_2_14_English.exe){: .button}

    [ASIO4ALL v2.13 Download](https://github.com/jamulussoftware/assets/raw/main/ASIO4ALL_2_13_English.exe){: .button}


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

<li>Make sure your interfaces, instruments/mics and headphones are plugged into your computer.</li>

<li>Close all other programs.</li>

<li>Run Jamulus and click on the <i>Settings</i> panel.</li>

<li>Click on <i>ASIO Device Setup</i>. This will open the ASIO4ALL setup window.
{% include screenshot.html file="asio-device-setup.png" alt="Asio device setup" %}
</li>

<li>Click on the wrench icon on the bottom right to enable advanced view.
{% include screenshot.html file="asio-setup-wrench.png" alt="ASIO4ALL advanced view toggle" %}
</li>

<li>Enable only the soundcard you want to use by clicking on the power button to the left. To see its inputs and outputs, click on the plus button and enable your inputs and outputs by clicking the power button next to its name.
{% include screenshot.html file="asio-setup-inputs.png" alt="ASIO4ALL setup for inputs/outputs" %}
</li>

<li>Go back to your Jamulus settings, and select your inputs and outputs under <i>Input Channel Mapping</i> and <i>Output Channel Mapping</i>.
{% include screenshot.html file="asio-setup-mapping.png" alt="Input/output channel mappings" %}
</li>

<li>To check if your audio is working correctly, connect to a server to hear your instrument or voice.</li>
</ol>

<i>If you have difficulty finding your internal sound cards, they are commonly named Realtek High Definition Audio, Conexant or similar.</i>

</p>
</div>
</div>


*Concerning the inputs/outputs: Headphones and speakers are often labelled as output and microphones as inputs or capture.*


## All set up?

Take a look at the onboarding page to get started with Jamulus!

[Jamulus Onboarding page](Onboarding){: .button}
