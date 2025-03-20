# Windows 11 Environment Setup

Watch the setup guide on YouTube: [Windows 11 Environment Setup](https://youtu.be/JUTdRZNqODY?si=BstOHqXD6EwVyeN4)

This guide outlines the steps to create a customized Windows 11 environment using Microsoft's Answer Files and a fresh installation of Windows 10 or 11.

## Tasks

- [ ] **1. Install and Configure Microsoft's Answer Files**  
  Microsoft's Answer Files (Unattend files) allow you to modify Windows settings and packages directly within the Windows ISO during setup. Use the following tools and resources to automate and customize your installation:  
  - [UnattendedWinstall](https://github.com/memstechtips/UnattendedWinstall) - Personalized unattended answer files to debloat and customize Windows 10 & 11 during installation.  
  - [Unattend Generator](https://schneegans.de/windows/unattend-generator/) - A web-based tool to generate custom unattended XML files.  
  - [Rufus](https://rufus.ie/en/) or [Balena Etcher](https://etcher.balena.io/) - Tools to create bootable USB drives for installing Windows with your custom answer file.

- [ ] **2. Install and Configure a Fresh Copy of Windows 10/11**  
  Perform a clean installation or upgrade to Windows 10 or 11 using official Microsoft ISOs:  
  - [Download Windows 10](https://www.microsoft.com/software-download/windows10) and use the Media Creation Tool to download an ISO or create installation media.
  - [Download Windows 11](https://www.microsoft.com/software-download/windows11)  
    - Serial Key: `W62VF-DNQ6W-9TB43-HRVGV-YY49F` (Use a valid license key for activation).

## Steps for Customization

### Using UnattendedWinstall
1. Download the `autounattend.xml` file from [UnattendedWinstall](https://github.com/memstechtips/UnattendedWinstall).
2. Place the `autounattend.xml` file at the root of your Windows installation media (USB or ISO).
3. Use a tool like Rufus or Etcher to create a bootable USB drive with the official Windows ISO.
4. Boot from the USB and follow the automated setup process.

# Windows Tools  
- [ ] 1. **Install Warp Terminal**: Modern terminal for developers. - [Download Warp](https://www.warp.dev/)  `winget install Warp.Warp`
- [ ] 2. Warp Drive: [Download Warp Drive](https://www.warp.dev/warp-drive) `winget install Warp.Warp`
> [!CAUTION]
> - [ ] 3. **Install Nushell**: A new shell for modern systems. - [Download Nushell](https://www.nushell.sh/)  
- [ ] 4. **Install Glasswire**: Monitor network activity and security. - [Download Glasswire](https://www.glasswire.com/)  
> [!CAUTION]
> - [ ] 5. **Chris Windows Debloat**: Optimize and debloat Windows. - [Chris Windows Debloat](https://github.com/ChrisTitusTech/winutil) *Run:* `irm "https://christitus.com/win" | iex`
- [ ] 6. **Encryption**: Secure your files with VeraCrypt. - [Download VeraCrypt](https://www.veracrypt.fr)
- [ ] 7. https://www.waveterm.dev/

# Windows Tasks  
1. **System File Checker**: Scan and repair corrupted system files. - Run: `sfc /scannow` in Command Prompt.
```
sfc /scannow
```
2. **DISM Command**: Repair Windows image. - Run: `DISM /Online /Cleanup-Image /RestoreHealth` in Command Prompt.
```
DISM /Online /Cleanup-Image /RestoreHealth
```
- [ ] 3. **Activate Windows Security Systems**: Enable built-in security features.
- [ ] 4. **Install Spotify Desktop**: Music streaming app. - [Download Spotify](https://www.spotify.com/download/)
- [ ] 5. **Graphics Card Drivers**: Install the latest drivers for your GPU. - [Download Drivers](https://www.gigabyte.com/Graphics-Card/GV-N166SOC-6GD/support#support-dl-utility)
- [ ] 6. **Manually Debloat Windows**: Remove unnecessary apps and services manually.
- [ ] 7. **Partition Hard Drives**: Organize storage by creating partitions.
- [ ] 8. **Create Shared Drives & Network**: Set up shared drives and network access.
- [ ] 9. **Create Remote Network**: Set up remote access to your network.

# Unix  
1. **Compositor**: Create dynamic window management. - [Hyprland](https://hyprland.org/)
2. https://nixos.org/
3. Arch Linux

# Bootloader
1. Super grub - https://www.supergrubdisk.org/
2. [https://www.waveterm.dev/](https://netboot.xyz)

# Security
1. https://www.kali.org
2. https://www.hackthebox.com/
3. https://tryhackme.com/

# VPN
1. https://www.twingate.com/

# VPS
1. https://my.vultr.com/
2. https://cloud.lambdalabs.com
3. https://console.paperspace.com

# Network  
1. **Zyxel Router**: Access your router settings. - [Access Zyxel Router](http://10.0.0.2/login/login.html) - User: `Admin` / Pass: `Admin`
2. https://checkmate.so/

# Security  
1. **Network Mapper**: Map and analyze network coverage. - [CellMapper](https://www.cellmapper.net)  
2. **Network VPN Security**: Secure your network with Netmaker. - [Netmaker](https://www.netmaker.io/)  
3. **Network VPN Security**: Secure your network with Twingate. - [Twingate](https://www.twingate.com/)  
4. **OSINT Face Search**: Search for faces using AI. - [PimEyes](https://pimeyes.com)

# Cloud  
1. **Install Opera**: Lightweight browser for simple use. - [Download Opera](https://www.opera.com/)  
2. **Install Firefox**: Main browser for bookmarks and syncing. - [Download Firefox](https://www.mozilla.org/firefox/)  
3. **Install Proton Drive**: Secure cloud storage. - [Download Proton Drive](https://proton.me/drive)  
4. **Install Google Drive**: Cloud storage and file synchronization. - [Download Google Drive](https://www.google.com/drive/)  
5. **Install Web Catalogue**: Organize and access web apps. - [Download Web Catalogue](https://webcatalog.io/)  
6. **Spotify Web**: Music streaming app. - [Open Spotify](https://open.spotify.com/)  
7. **Raindrop.io**: Bookmark manager and organizer. - [Visit Raindrop](https://raindrop.io/)  
8. **Cloud Cataloging**: Organize your cloud data. - [Mori](https://www.mori.co/)  
9. **Maps**: Create custom maps. - [Google My Maps](https://www.google.com/mymaps/)  
10. **Cloud Storage**: Store your files securely. - [Icedrive](https://icedrive.net)  
11. **Maps**: Explore the world. - [Google Earth](https://earth.google.com)

# Cloud Computing  
1. **Google Colab**: Develop and run Python code in the cloud. - [Google Colab](https://colab.google/)  
2. **Oracle Cloud**: Cloud computing services. - [Oracle Cloud](https://www.oracle.com/cloud)  
3. **DigitalOcean**: Cloud infrastructure provider. - [DigitalOcean](https://www.digitalocean.com/)  
4. **Linode**: Cloud hosting provider. - [Linode](https://www.linode.com/)  
5. **Pomerium**: Secure access to internal applications. - [Pomerium](https://www.pomerium.com/)  
6. **Tailscale**: Secure network connections. - [Tailscale](https://tailscale.com/)  
7. **Anaconda**: Data science platform. - [Anaconda](https://www.anaconda.com)  

# Communication  
1. **Email: Thunderbird**: Connect email accounts and calendars. - [Download Thunderbird](https://www.thunderbird.net/)  
2. **Proton Mail (Web Catalogue)**: Secure email service. - [Download Web Catalogue](https://webcatalog.io/)  
3. **Install WhatsApp Desktop**: Desktop version of WhatsApp. - [Download WhatsApp](https://www.whatsapp.com/download)  // * Cloud Version - https://web.whatsapp.com/ * //  
4. **Shortwave**: Email client with AI-powered features. - [Visit Shortwave](https://app.shortwave.com/)  
5. **Google Messages**: Send and receive messages. - [Google Messages](https://messages.google.com)  
6. **Contacts**: Manage your contacts. - [Contacts+](https://contactsplus.com)  
7. **Email**: Access your email. - [Gmail](https://mail.google.com)

# Webcam
1. GoPro Webcam

# Admin  
1. **Project Management: Clickup**: All-in-one project management tool. - [Visit Clickup](https://www.clickup.com/)  
2. **Proton Apps**: Access Proton's suite of privacy-focused apps. - [Proton Apps](https://account.proton.me/apps)  
3. **Password Management**: Manage your passwords securely. - [Bitwarden](https://bitwarden.com)  

# Personal  
1. **Carrd**: Create simple one-page websites. - [Visit Carrd](https://mariomorgan.carrd.co/)

# Life  
1. **Timeline**: Create timelines. - [Time Graphics](https://time.graphics)  
2. **Genealogy**: Trace your ancestry. - [Ancestry](https://www.ancestry.com/)  
3. **Genealogy**: Trace your ancestry. - [Mori](https://www.mori.co/)  

# Home  
1. **Security Cameras**: Monitor your home security cameras. - [Hik-Connect](https://ieu.hik-connect.com)  
2. **Google Home**: Manage your smart home devices. - [Google Home](https://home.google.com)

# Live // Split Screen  
1. **Emergency & Disaster**: Track global emergencies and disasters. - [RSOE EDIS](https://rsoe-edis.org/eventmap)  
2. **Conflict Tracker**: Monitor global conflicts. - [Global Conflict Tracker](https://www.cfr.org/global-conflict-tracker)  
3. **Disaster Alerts**: Get real-time disaster alerts. - [Disaster Alert](https://disasteralert.pdc.org/disasteralert/)

# Car Management  
1. **Driver Technologies**: AI-powered driver assistance. - [Visit Driver Technologies](https://drivertechnologies.com/)  
2. **Topdon**: Automotive diagnostic tools. - [Visit Topdon](https://www.topdon.com/products/TopScan)  

# Gaming  
1. **Steam**: Gaming platform for PC. - [Visit Steam](https://store.steampowered.com/)  
2. **Ubisoft**: Gaming platform for Ubisoft games. - [Visit Ubisoft](https://www.ubisoft.com/)  
3. **Epic Games**: Gaming platform for PC. - [Visit Epic Games](https://www.epicgames.com/store/)

# Work  
1. **Install Airbnb (Web Catalogue)**: Access Airbnb via the Web Catalogue app. - [Download Web Catalogue](https://webcatalog.io/)  
2. **Business Process Simulator**: Simulate and optimize business processes. - [Visit BPSimulator](https://www.bpsimulator.com)

# Property Management  
1. **Host Sharing**: Share your property. - [Hostshare](https://www.hostshare.co/)  
2. **Accommodation**: Find accommodations. - [Lekkeslaap](https://www.lekkeslaap.co.za)  
3. **Accommodation Analysis**: Analyze short-term rental markets. - [Airbtics](https://airbtics.com/)  

# Business  
1. **Business Hub**: Access business resources and tools. - [GovChain](https://www.govchain.co.za/)  
2. **Trademarks & Patents**: Manage intellectual property. - [RightHub](https://righthub.com/)  
3. **Professional Networking**: Connect with professionals. - [Intch](https://intch.org/)  
4. **Data & Lead Scraper**: Scrape data and leads. - [PhantomBuster](https://phantombuster.com/)  
5. **Business & Lead Connections**: Find business leads. - [Lusha](https://www.lusha.com/)  
6. **Business & Lead Connections**: Connect with startups. - [F6S](https://www.f6s.com/)  
7. **Service Providers**: Find service providers. - [Sortlist](https://www.sortlist.com/)  
8. **CIA World Factbook**: Access global intelligence data. - [CIA World Factbook](https://www.cia.gov/the-world-factbook/)
9. https://www.harvey.ai/

# Retail  
1. **On Demand Printing**: Print on demand. - [Printful](https://www.printful.com/)  
2. **Online Marketplace**: Sell on Etsy. - [Etsy](https://www.etsy.com)  
3. **Online Store**: Create an online store. - [Shopify](https://shopify.com)  
4. **Online Marketplace**: Sell on Takealot. - [Takealot](https://www.takealot.com/sell)  
5. **Online Marketplace**: Sell on Alibaba. - [Alibaba](https://seller.alibaba.com/)  
6. **Online Marketplace**: Sell on Amazon. - [Amazon](https://sellercentral.amazon.com/)  
7. **Etsy Analysis**: Analyze Etsy data. - [Listadum](https://www.listadum.com/)  
8. **Seller Tool**: Manage your sales. - [Vela](https://getvela.com/)  
9. **Seller Tool**: Manage your sales. - [Alura](https://www.alura.io/)  
10. **Seller Tool**: Manage your sales. - [Marmalead](https://marmalead.com/)  
11. **Seller Tool**: Manage your sales. - [Ehunt](https://ehunt.ai)  

# Merchandising  
1. **Sewing Patterns**: Create sewing patterns. - [Lekala](https://www.lekala.co/)

# Finance  
1. **Banking**: Manage your finances. - [22seven](https://www.vault22.io)  
2. **Accounting**: Manage your accounts. - [Wave](https://waveapps.com)  
3. **Accounting**: Manage your accounts. - [Xero](https://xero.com)  
4. **Receipts**: Manage your receipts. - [SparkReceipt](https://sparkreceipt.com)
5. Crypto Wallet & Exchange: https://www.exodus.com/
6. Luno

# Trading  
1. **Financial Data**: Access financial data. - [Trading Economics](https://tradingeconomics.com/)  

# Documents  
1. **Tool**: Manage PDFs. - [ILovePDF](https://www.ilovepdf.com/)  
2. **Tools**: Access various tools. - [The Tool Bus](https://www.thetoolbus.ai/)  
3. **OCR**: Convert images to text. - [OCR Space](https://ocr.space/)  
4. **Document Publishing**: Publish documents online. - [Issuu](https://issuu.com)
5. https://www.humanizer.pro/
6. https://originality.ai/
7. https://www.quadratichq.com/
8. https://rows.com
9. https://numerous.ai/
10. https://www.sheetai.app/
11. https://www.gigasheet.com/

# Notes & Research  
1. **Windows Notepad**: Built-in text editor for quick notes.  
2. **Notebook LLM (Web Catalogue)**: AI-powered note-taking tool. - [Download Web Catalogue](https://webcatalog.io/) - *Cloud Version*: [NotebookLM](https://notebooklm.google.com/)  
3. **Perplexity.ai**: AI-powered research and question-answering tool. - [Visit Perplexity](https://www.perplexity.ai/)  
4. **Julius.ai**: AI-powered data analysis and visualization tool. - [Visit Julius](https://julius.ai/)  
5. **Perplexity**: AI-powered research tool. - [Perplexity](https://www.perplexity.ai/)

# Data  
1. **World Bank**: Access global development data. - [World Bank Data](https://data.worldbank.org/)  
2. **Humdata**: Access humanitarian data. - [Humdata](https://data.humdata.org/)  
3. **Statista**: Access statistical data. - [Statista](https://www.statista.com/)  
4. **WHO**: Access global health data. - [WHO](https://www.who.int/)  
5. **OECD**: Access economic data. - [OECD](https://www.oecd.org/)  
6. **Worldometers**: Access real-time world statistics. - [Worldometers](https://www.worldometers.info/)  
7. **Data Commons**: Access public datasets. - [Data Commons](https://datacommons.org/)  
8. **DHS**: Access demographic and health surveys. - [DHS](https://dhsprogram.com/)  

# Mind Mapping  
1. **Obsidian**: Create and manage mind maps. - [Download Obsidian](https://obsidian.md/)  
2. **Milanote**: Visual collaboration tool for organizing ideas. - [Visit Milanote](https://app.milanote.com)  
3. **Mindmap AI**: AI-powered mind mapping tool. - [Visit Mindmap AI](https://mindmapai.app/canvas)  
4. **Whimsical**: Collaborative visual workspace. - [Visit Whimsical](https://whimsical.com)

# Design  
1. **Affinity Designer**: Professional graphic design software. - [Download Affinity Designer](https://affinity.serif.com/designer/)  
2. **Affinity Publisher**: Professional publishing software. - [Download Affinity Publisher](https://affinity.serif.com/publisher/)  
3. **Install SeaArt.ai (Web Catalogue)**: AI-powered art and design tool. - [Download Web Catalogue](https://webcatalog.io/)  
4. **Assets**: Access design assets. - [Pixelbin](https://www.pixelbin.io/)  
5. **Assets**: Access design assets. - [Design Lobby](https://designlobby.app/)

# Design  
1. **Vectorizer**: Convert images to vectors. - [Vectorizer](https://vectorizer.ai/)  
2. **Vectorizer**: Convert images to vectors. - [VectorArt](https://vectorart.ai/)  
3. **Vectorizer**: Convert images to vectors. - [ImgVector](https://imgvector.com/)  
4. **Patterns**: Create patterns with AI. - [Patterned](https://www.patterned.ai/)  
5. **Design Generator**: Generate designs with AI. - [Playground](https://playground.com/)  
6. **Stock Design, Photo & Video**: Access stock assets. - [Vecteezy](https://www.vecteezy.com)  
7. **Stock Photo & Video**: Access stock assets. - [Pexels](https://www.pexels.com)  
8. **Image Upscaler**: Upscale images with AI. - [ImgUpscaler](https://imgupscaler.com)  
9. **Image Tools**: Enhance and edit images. - [Magnific](https://magnific.ai/)  
10. **Image Tools**: Enhance and edit images. - [ImgLarger](https://imglarger.com/)

# Motion
1. https://lottiefiles.com/
2. https://jitter.video/

# AI Content Generators  
1. **All**: AI-powered content generation. - [Hedra](https://www.hedra.com/) Film
2. **All**: AI-powered content generation. - [Kling AI](https://klingai.com/) Film 3
3. **Video**: Generate videos with AI. - [Pixverse](https://app.pixverse.ai)  Film 2
13. **Film**: Create films with AI. - [SkyReels](https://www.skyreels.ai) Film 4
5. **Film**: Create films with AI. - [LTX Studio](https://ltx.studio/)  Storyboarding
6. **Video**: Generate videos with AI. - [Dream Machine](https://dream-machine.lumalabs.ai/)  Anime / Manga
7. **Image Generation**: Generate images with AI. - [OpenArt](https://openart.ai) Studio Tools
8. **All**: AI-powered content generation. - [Kive](https://kive.ai/)  Studio Tools
9. **Image Generation**: Generate images with AI. - [BasedLabs](https://www.basedlabs.ai/) Studio Tools
10. **Image Generation**: Generate images with AI. - [Imagine](https://www.imagine.art/) Studio Tools
11. **All**: AI-powered content generation. - [Runway](https://runwayml.com/)  Studio Tools
12. https://app.rendernet.ai studio  tools
13. 15. **Video**: Edit videos with AI. - [VEED](https://www.veed.io/)  video tools

14. 14. **Video Characters**: Create video characters with AI. - [D-ID](https://www.d-id.com/)  Video Avatars

4. **Video Generator**: Generate videos with AI. - [Genmo](https://www.genmo.ai/)  Image to Video Motion
5. **All**: AI-powered content generation. - [Immersity](https://www.immersity.ai/)  video motion

17. **All**: AI-powered content generation. - [Arvin](https://arvin.chat/)  personal assistant / design tools

20. **All**: AI-powered content generation. - [Clipdrop](https://clipdrop.co/)  design tools
21. **All**: AI-powered content generation. - [Cutout](https://www.cutout.pro/)  design tools
22. **All**: AI-powered content generation. - [Getimg](https://getimg.ai/)  design tools
23. **All**: AI-powered content generation. - [Eluna](https://www.eluna.ai/)  design tools
24. **Image Generation**: Generate images with AI. - [Krea](https://www.krea.ai/)  design tools

29. **Image Generation**: Generate images with AI. - [Civitai](https://civitai.com/)  Image Models
31. **Image Generation**: Generate images with AI. - [SeaArt](https://www.seaart.ai/)  Image Creation
32. **Image & 3D Model Creation**: Create images and 3D models with AI. - [CG Dream](https://cgdream.ai/)  image creation
33. **Image Generation**: Generate images with AI. - [Impossible Images](https://impossibleimages.ai/)  image creation
34. **Image & Video Enhancer**: Enhance images and videos with AI. - [TensorPix](https://tensorpix.ai/)  image and video enhancer

35. **Image Generation**: Generate images with AI. - [Black Forest Labs](https://blackforestlabs.ai/)   https://github.com/camenduru/flux-jupyter/blob/main/flux.1-dev_jupyter.ipynb
36. https://www.piclumen.com/
37. https://github.com/ehristoforu/DeFooocus/tree/main
38. https://github.com/lllyasviel/Fooocus/tree/main
40. https://www.midjourney.com
41. https://www.rokoko.com/products/vision
42. https://metahuman.unrealengine.com/
43. https://www.storyblocks.com/

# Prototyping  
1. **Figma**: Collaborative design and prototyping tool. - [Visit Figma](https://www.figma.com/)  
2. **Prototyping**: Create interactive prototypes. - [Quant-UX](https://app.quant-ux.com)

# 3D  
1. **Model Creation**: Create 3D models. - [Hyper3D](https://hyper3d.ai/)  
2. **Model Creation**: Create 3D models. - [Meshy](https://www.meshy.ai/)  
3. **Unity Cloud**: Cloud services for Unity. - [Unity Cloud](https://cloud.unity.com)  
4. **Model Poser**: Pose 3D models. - [Open Pose Editor](https://zhuyu1997.github.io/open-pose-editor/)
5. https://spline.design/

# Game Dev
1. https://rive.app/

# Voice  
1. **Fish Audio**: Voice cloning, voice library, voiceover, and more. - [Visit Fish Audio](https://fish.audio/)  

# Music  
1. **Playlist Transfer**: Transfer playlists between music services. - [TuneMyMusic](https://www.tunemymusic.com/)  
2. **DJ Software**: Mix music with DJ software. - [Mixxx](https://mixxx.org/)  
3. **Sound Engineering**: Enhance sound quality. - [LANDR](https://www.landr.com/)  
4. **Sample Library**: Access a library of samples. - [SampleFocus](https://samplefocus.com/)  
5. **Cloud DAW**: Create music in the cloud. - [Amped Studio](https://ampedstudio.com)  
6. **Remote Production**: Collaborate on music production. - [Source Elements](https://www.source-elements.com/)  
7. **Cloud DAW**: Create music in the cloud. - [Audiotool](https://www.audiotool.com/)  
8. **Cloud Production**: Collaborate on music production. - [Boombox](https://boombox.io/)
9. https://www.riffusion.com
10. https://suno.com

# Image  
1. **Compression**: Compress images. - [Compressor](https://compressor.io/) 

# Photography  
1. **Photo Generation**: Generate photos with AI. - [PhotoAI](https://photoai.com/)  
2. **Photo Editor**: Edit photos with AI. - [Fotor](https://www.fotor.com/)  
3. **Image Organization**: Organize your photos. - [Eden Photos](https://edenphotos.io/)  
4. **Photo Tools**: Enhance and edit photos. - [Pica AI](https://www.pica-ai.com/)  
5. **Photo Scaler**: Upscale photos with AI. - [QualityScaler](https://github.com/Djdefrag/QualityScaler)  
6. **Photo Tools**: Enhance and edit photos. - [Picma](https://picma.magictiger.ai/)  
7. **Photo & Video Enhancer**: Enhance photos and videos with AI. - [Remini](https://app.remini.ai/)  
8. **Photo Metadata**: View and edit photo metadata. - [Exif Photos](https://exif.photos/)  
9. **Photo Metadata**: View and edit photo metadata. - [Metadata2Go](https://www.metadata2go.com/)  
10. **Photo Metadata**: View and edit photo metadata. - [Jimpl](https://jimpl.com)  
11. **Photo Metadata**: View and edit photo metadata. - [Image Metadata Checker](https://imagemetadatachecker.com)  
12. **Photo Geo & Metadata**: View photo geolocation and metadata. - [Geocords](https://www.geocords.com/)  
13. **Photo Geolocation**: View photo geolocation. - [Picarta](https://picarta.ai/)  
14. **Photo Tools**: Enhance and edit photos. - [Picwish](https://picwish.com/)  
15. **Contact Sheets**: Create contact sheets. - [Contact Sheet Maker](https://www.contactsheetmaker.com/)  
16. **Photo & Video Enhancer**: Enhance photos and videos with AI. - [Topaz Labs](https://www.topazlabs.com/)  
17. **Photo Editor**: Edit photos with AI. - [Pixelcut](https://www.pixelcut.ai/)  
18. **Photo Upscaler**: Upscale photos with AI. - [Upscayl](https://upscayl.org/)
19. https://letsenhance.io/

# Video  
1. **Screen Writing**: Write screenplays. - [Arc Studio Pro](https://www.arcstudiopro.com/)  
2. **Cloud Sync**: Sync your video projects. - [Blackmagic Cloud](https://cloud.blackmagicdesign.co)  
3. **Video Broadcasting**: Broadcast live video. - [OBS](https://obsproject.com/)  
4. **Streaming**: Stream live video. - [Streamlabs](https://streamlabs.com/)  
5. **Stock Video**: Access stock video assets. - [Videvo](https://www.videvo.net)  
6. **Stock Photo & Video**: Access stock assets. - [Pixabay](https://pixabay.com)  
7. **Video Tools**: Edit and enhance videos. - [Clideo](https://clideo.com/)  
8. **Video Editor**: Edit videos with AI. - [Flixier](https://flixier.com/)  
9. **Video Editor**: Edit videos with AI. - [Capcut](https://www.capcut.com/)  
10. **Film Inspiration**: Get inspired for filmmaking. - [Shot Cafe](https://shot.cafe/)
11. https://vidiq.com/
12. https://addons.mozilla.org/en-US/firefox/addon/viewstats-youtube-analytics/
13. https://socialblade.com/youtube/

# Coding Development Environment  
1. **Github Desktop**: GUI for managing Git repositories. - [Download](https://desktop.github.com/)  
2. **Github CoPilot**: AI-powered code completion tool. - [Learn More](https://copilot.github.com/) - *Cloud Version*: [Github CoPilot](https://github.com/copilot)  
3. **Github Codespaces**: Cloud-based development environments. - [Learn More](https://github.com/features/codespaces) - *Cloud Version*: [Github Codespaces](https://github.com/codespaces)  
4. **Github Actions**: Automates builds, tests, and deployments. - [Learn More](https://github.com/features/actions)  
5. **Github Pages**: Host static websites. - [Github Pages](https://pages.github.com/)  
6. **Git**: Version control system. - [Git](https://git-scm.com/)  
7. **Visual Studio Code**: Lightweight, extensible code editor. - [Download](https://code.visualstudio.com/)  //  * Cloud  Version - https://vscode.dev/ * //  
8. **Supabase**: Open-source Firebase alternative. - [Learn More](https://supabase.com/) - *Cloud Version*: [Supabase](https://supabase.com/)  
9. **Docker**: Containerization platform for building and deploying apps. - [Download](https://www.docker.com/)  
10. **StackBlitz**: Online IDE for web development. - [Visit](https://stackblitz.com/) - *Cloud Version*: [StackBlitz](https://stackblitz.com/)  
11. **Gist**: Share and save code snippets. - [Visit](https://gist.github.com/) - *Cloud Version*: [Gist](https://gist.github.com/)  
12. **Tailwind CSS**: Utility-first CSS framework for rapid UI development. - [Learn More](https://tailwindcss.com/)  
13. **Vercel**: Platform for deploying and hosting frontend applications. - [Visit](https://vercel.com/)  
14. **Node.JS**: JavaScript runtime for building server-side applications. - [Download](https://nodejs.org/)  
15. **Next.JS**: React framework for server-rendered and static websites. - [Learn More](https://nextjs.org/)  
16. **Sentry**: Tracks and fixes errors in real-time. - [Learn More](https://sentry.io/)  
17. **New Relic**: Monitors application performance and infrastructure. - [Learn More](https://newrelic.com/)  
18. **Bolt.new**: AI-powered coding assistant for faster development. - [Visit](https://bolt.new/) - *Can Install Locally*: [Bolt DIY](https://github.com/stackblitz-labs/bolt.diy)  
19. **Fleek**: Builds and deploys decentralized apps and AI agents. - [Learn More](https://fleek.xyz/)  
20. **Arweave**: Decentralized storage for permanent data archiving. - [Learn More](https://arweave.org/)  
21. **LambdaTest**: Testing web apps. - [Learn More](https://www.lambdatest.com/)  
22. **Cursor**: AI-powered code editor. - [Visit Cursor](https://www.cursor.com/)  
23. **Pipedream**: API integration platform. - [Visit Pipedream](https://pipedream.com/)  
24. **GPT**: AI development platform. - [Google AI Studio](https://aistudio.google.com)  
25. **Android Development**: Develop Android apps. - [Android Developer](https://developer.android.com/)  
26. **Databases**: Manage databases. - [MySQL](https://www.mysql.com/)  
27. **Electron**: Build cross-platform desktop apps. - [Electron](https://www.electronjs.org/)  
28. **AI APIs**: Access AI APIs. - [Replicate](https://replicate.com)
29. https://graphite.dev/
30. https://codeium.com/
31. https://www.tempo.new/

# CODING LIBRARIES
1. React: npm install react react-dom
2. Python: winget install Python.Python.3.12
3. Node.js: winget install OpenJS.NodeJS
4. UV: pip install uv
6. vite: npm install -g vite

# Python Libraries
1. // Run pip install // pygame for graphics.
2. Optionally, // pip install numpy // for faster math operations.
3. // pip install taichi // A Python library for high-performance physics simulations

# MCP SERVERS ( https://www.youtube.com/watch?v=yOKwK-iIg3M )
1. https://github.com/anaisbetts/mcp-installer
2. https://github.com/modelcontextprotocol/servers

# Web Development  
1. **Webflow**: Visual web development platform. - [Visit Webflow](https://webflow.com/)  
2. **App Builder**: Build apps with FlutterFlow. - [FlutterFlow](https://flutterflow.io)  
3. **App Builder**: Build apps with Codux. - [Codux](https://www.codux.com/)  
4. **Web Hosting**: Free web hosting. - [InfinityFree](https://www.infinityfree.com/)  
5. **Web Hosting**: Affordable web hosting. - [Hostinger](https://www.hostinger.com)  
6. **Website Builder**: Build websites easily. - [Wix](https://www.wix.com/)
7. https://www.polymet.ai/
8. https://v0.dev/

# Electronics  
1. **Arduino**: Develop electronic projects. - [Arduino](https://www.arduino.cc)  
2. **Electronic User Interfaces**: Develop user interfaces. - [Electric UI](https://electricui.com/)  
3. **Design & Development**: Develop cross-platform applications. - [Qt](https://www.qt.io/)  
4. **UI Library**: Create graphical user interfaces. - [LVGL](https://lvgl.io/)  
5. **Interface Design & Development**: Design and develop interfaces. - [Squareline](https://squareline.io/)  
6. **Tinkercad**: Create 3D designs. - [Tinkercad](https://tinkercad.com)  

# AI Environment  
1. **Self Operating Computer**: AI-powered automation tool for computer tasks. - [Visit Hyperwrite AI](https://www.hyperwriteai.com) | [GitHub Repository](https://github.com/OthersideAI/self-operating-computer) *(Not Free)*

# AI Tools  
1. **Scraper**: Scrape data from websites. - [Browse AI](https://www.browse.ai/)  
2. **Transcription**: Transcribe audio and video. - [Cockatoo](https://www.cockatoo.com/)  
3. **Legal**: AI-powered legal assistance. - [AI Lawyer](https://ailawyer.pro/)  
4. **AI Training**: Train AI models. - [Gymnasium](https://gymnasium.farama.org/)  
5. **AI Model Creation**: Create AI models. - [TensorFlow](https://www.tensorflow.org/)  
6. **AI Creation and Training**: Create and train AI models. - [OpenAI](https://platform.openai.com)
7. MCP Server: https://github.com/anaisbetts/mcp-installer // Claude
8. https://www.runpod.io/
9. https://www.gradio.app/

# AI LLMs  
1. **Ollama**: Run Llama 3.3, DeepSeek-R1, Phi-4, Mistral, Gemma 2, and other models locally. - [Visit Ollama](https://ollama.com/)

# AI GPTs  
1. **Install Deepseek (Web Catalogue)**: AI tool for advanced tasks and automation. - [Download Web Catalogue](https://webcatalog.io/)  
2. **Gemini**: AI-powered assistant. - [Gemini](https://gemini.google.com/)  
3. **Meta**: AI-powered assistant. - [Meta AI](https://www.meta.ai/)  
4. **Grok**: AI-powered assistant. - [Grok](https://grok.com/)  
5. **ChatGPT**: AI-powered chatbot. - [ChatGPT](https://chatgpt.com/)  
6. **Deepseek**: AI-powered assistant. - [Deepseek](https://chat.deepseek.com)  
7. **Blackbox**: AI-powered assistant. - [Blackbox](https://www.blackbox.ai/)
8. Claude: https://claude.ai
9. https://chat.mistral.ai/
10. https://convergence.ai/
11. https://aistudio.google.com/live
12. https://manus.im/
13. novaapp.ai

# AI Agents  
1. **Make.com**: Automation platform for workflows. - [Visit Make](https://make.com/)  
2. **n8n.io**: Open-source workflow automation tool. - [Visit n8n](https://n8n.io/)  
3. **Vapi.ai**: Voice AI platform for building voice assistants. - [Visit Vapi](https://vapi.ai/)  
4. **AutoGPT**: AI-powered automation tool. - [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)  
5. **DialogueFlow**: Build conversational agents. - [Dialogflow](https://dialogflow.cloud.google.com)
6. https://pipedream.com

# Conversational AI Agents
1. https://flowgent.ai/
