# DuoClip

### Turn long videos into short, creator-ready clips.

**DuoClip** is a free-to-download, local-first video clipping and caption studio for **Windows**. It brings video import, transcription, clip preparation, caption styling, smart reframing, branding, and export together in one desktop application.

**Windows 10 / 11 (64-bit)** · **Free download** · **Local-first processing** · **Source code not published**

> **Release status:** DuoClip is currently an early `0.1.0` build. Features and hardware support are still being tested. Public installer downloads will be listed under **Releases** once a build has completed installation and export checks.

## Download DuoClip

When a tested installer is published:

1. Open the [**Releases**](../../releases) page.
2. Select the latest published version.
3. Under **Assets**, download the Windows installer named like `DuoClip-Setup-0.1.0.exe`.
4. Run the installer, then launch DuoClip from the desktop or Start menu.
5. On first launch, use the setup wizard to check or download any required processing components and AI models.

**Important:** Download the `.exe` from **Release assets**, **not** GitHub's automatically generated “Source code (zip)” or “Source code (tar.gz)” files. Those are not Windows installers. If no installer appears under Releases yet, the public download has not been published.

## What is DuoClip?

DuoClip is designed to help video creators turn longer recordings into shorter, more engaging videos while keeping their editing workflow on their own computer. Instead of switching between several tools, you can organize projects, configure clips, select caption designs, add channel branding, and prepare vertical videos within one desktop workspace.

### Main features

| Feature | What it does |
| --- | --- |
| **Local video and YouTube import** | Start from a supported video file on your PC or import a YouTube video you're authorized to use. |
| **Short-form video workflow** | Create clips from longer footage and configure aspect ratio, clip duration, and selection preferences. |
| **Speech transcription** | Use installed local speech models to turn spoken audio into text for captioning and editing. |
| **Speaker-aware processing** | Access speaker diarization and voice activity tools when their required components are installed. |
| **Smart Reframe** | Configure reframing for vertical videos, with face/speaker-aware features where supported. Results depend on footage and models. |
| **Caption Studio** | Browse **26 caption styles** shown in the current interface, including ready-made, clean, motion-inspired, and custom designs. |
| **Typography and color controls** | Adjust captions with font choices, size, word grouping, spacing, alignment, and highlight colors. |
| **Brand Kit** | Add channel identity elements, watermark text, a logo, and customizable outro details. |
| **Vertical live preview** | Preview caption and end-screen designs in a 9:16 layout before rendering. |
| **Project management** | Keep video workflows organized as local projects, with a processing queue and project list. |
| **Hardware and setup checks** | Detect available CPU/GPU resources and manage required runtimes and AI models. |

## How does it work?

1. **Create a project.** Choose a local video, or supply a YouTube source you have permission to use.
2. **Choose clip settings.** Select the output aspect ratio, clip length, processing mode, and clip-selection options.
3. **Prepare AI tools.** Install or select the models needed for transcription, speaker processing, and smart reframing.
4. **Process your video.** Work through transcription, speakers, clip selection, and related project steps.
5. **Style the result.** Choose caption presets, customize text appearance, and add channel branding or an end screen.
6. **Preview and export.** Review your choices and render the finished video using the available local processing components.

Some functions require a compatible speech or vision model. Features such as transcription accuracy, speaker tracking, and export speed depend on the video, the selected settings, and your hardware.

## Screenshots

The screenshots below are taken from the DuoClip Windows application.

### New Project — import your video

![DuoClip New Project screen](screenshots/01-new-project.png)

### First-run setup — prepare local components and AI models

![DuoClip first-run setup screen](screenshots/02-first-run-setup.png)

### Caption styles — browse preset designs

![DuoClip caption styles gallery](screenshots/04-caption-library.png)

### Project setup — adjust clips, captions, and preview

![DuoClip project setup and vertical live preview](screenshots/06-project-setup.png)

### Channel branding — watermark, logo, and end screen

![DuoClip branding controls and end screen preview](screenshots/07-branding.png)

<details>
<summary><strong>More screenshots — Projects and Settings</strong></summary>

#### Projects

![DuoClip projects screen](screenshots/03-projects.png)

#### Settings and system checks

![DuoClip settings screen](screenshots/05-settings.png)

</details>

## Is DuoClip offline? What happens to my files?

**DuoClip is local-first.** Its desktop project workflow and supported media processing are designed to run on your Windows PC. Local source videos and project files are handled on the computer rather than requiring you to upload each project to a hosted editing service.

There are important exceptions:

- **Internet is needed for initial downloads** of processing runtimes or AI models that are not already installed.
- **YouTube importing needs internet access** and should only be used for videos you are authorized to download or process.
- **Hardware acceleration and some AI features depend on the system.** Not every PC will support every GPU or model configuration.
- **Check your own privacy and network requirements** before using third-party download sources, update checks, or externally hosted content.

Once its required components are available, supported local workflows can operate without an ongoing cloud editing service. This does **not** mean every DuoClip feature works without internet.

## System requirements

| Requirement | Details |
| --- | --- |
| Operating system | Windows 10 or Windows 11, 64-bit |
| Storage | Enough free space for the app, AI models, original footage, temporary processing files, and exports |
| Memory | Requirements vary with video resolution and selected processing models; more RAM helps with demanding projects |
| Processor | Modern 64-bit Windows CPU |
| Graphics | Compatible NVIDIA GPU may accelerate supported tasks; GPU support is not universal |
| Internet | Required for initial missing-component/model downloads and online video import |

Minimum hardware requirements have not yet been finalized for a public stable release.

## First-time installation

1. Download the `.exe` from [Releases](../../releases) when available.
2. Install DuoClip using the Windows setup wizard. Some installation paths may require administrator approval.
3. Open DuoClip and review the first-run component checker.
4. Download or locate missing components, including speech and optional vision/speaker models as needed.
5. When the setup reports that the necessary components are ready, continue into the Create workspace.

If Windows flags the installer as unrecognized, verify that you downloaded it from this project's official release and check its published checksum where available. **Do not disable Windows security protections to force installation.**

## Who is DuoClip for?

DuoClip is intended for video creators, podcasters, educators, interview editors, and teams producing short-form content from recordings they own or are permitted to use.

## Demo video

A walkthrough will be added here showing import → setup → captions → branding → preview → export.

*Demo video: coming soon.*

## Issues and feedback

Found a bug or have a suggestion? Open a [GitHub Issue](../../issues) and include your Windows version, the DuoClip version, the steps to reproduce the problem, and a screenshot or non-sensitive error message. Please **do not post private videos, credentials, system tokens, or personal paths** in a public issue.

## Distribution and source code

**DuoClip is free to download, but it is not published as an open-source project.** This repository is for public information, screenshots, and compiled installer releases only. It does not contain DuoClip's proprietary application source, internal build tools, or private development files.

Third-party components and models remain subject to their respective licenses and distribution terms. Review any notices included with the installer or published release. Download and process only media that you have the rights to use.

---

**DuoClip** — *Short clips. Big impact.*
