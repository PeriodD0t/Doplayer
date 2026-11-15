# Third-party notices

Doplayer includes the following open-source software. Licence texts are in each project's repository (links below).

## Linked statically into the Doplayer executable

| Component | Licence | Copyright |
|---|---|---|
| SFBAudioEngine (and AVFAudioExtensions, CXXAudioRingBuffer, CXXDispatchSemaphore, CXXMessageQueue, CXXQueue, CXXUnfairLock) | MIT | © 2006–2026 Stephen F. Booth |
| TagLib (via CXXTagLib) | Mozilla Public License 1.1 (TagLib is dual-licensed LGPL 2.1 / MPL 1.1; used here under MPL 1.1) | © TagLib authors (Scott Wheeler, Lukáš Lalinský, Allan Sandfeld Jensen and others) |
| Monkey's Audio SDK (via CXXMonkeysAudio) | Monkey's Audio License (3-clause BSD) | © 2000–2026 Matthew T. Ashland |
| Speex (via CSpeex) | BSD 3-clause (Xiph.org) | © 2002–2008 Xiph.org Foundation, Jean-Marc Valin |
| DUMB (via CDUMB) | DUMB licence (zlib-style permissive) | © 2001–2005 Ben Davis, Robert J. Ohannessian, Julien Cugniere |

## Bundled as dynamic frameworks (Doplayer.app/Contents/Frameworks)

| Framework | Licence | Copyright |
|---|---|---|
| FLAC | BSD 3-clause (libFLAC) | © 2000–2009 Josh Coalson, © 2011–2023 Xiph.Org Foundation |
| ogg | BSD 3-clause | © 2002 Xiph.org Foundation |
| vorbis | BSD 3-clause | © 2002–2020 Xiph.org Foundation |
| opus | BSD 3-clause | © 2001–2023 Xiph.Org, Skype Limited, Octasic and others |
| wavpack | BSD 3-clause | © 1998–2025 David Bryant |
| mpc (Musepack) | BSD 3-clause / LGPL (dual) | © 2005 The Musepack Development Team |
| **lame** | **GNU LGPL 2** | © LAME developers |
| **mpg123** | **GNU LGPL 2.1** | © 1995–2020 Michael Hipp and others |
| **sndfile (libsndfile)** | **GNU LGPL 2.1** | © Erik de Castro Lopo and contributors |
| **tta-cpp** | **GNU LGPL 3** | © TTA authors |

The LGPL components are separate dynamic frameworks inside the app bundle and can be replaced by the user with compatible builds. Their source code is available from the upstream projects and from https://github.com/sbooth (the *-binary-xcframework packages used to build Doplayer).

No GPL (non-Lesser) components are included.

Project links: SFBAudioEngine https://github.com/sbooth/SFBAudioEngine · TagLib https://taglib.org · Xiph.org https://xiph.org · WavPack https://www.wavpack.com · Monkey's Audio https://www.monkeysaudio.com · mpg123 https://www.mpg123.de · LAME https://lame.sourceforge.io · libsndfile https://libsndfile.github.io/libsndfile/ · Musepack https://www.musepack.net · TTA https://tausoft.org
