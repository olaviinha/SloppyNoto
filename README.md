# Sloppy Noto

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/SloppyNoto/blob/master/sloppyNoto.ipynb)

Sloppy Noto is a data audiolizer. It turns numeric data into sound.

- 🚫 Noto **does not** oscillate or generate sound waves by other means _based_ on given data, modify any such waves, or take artistic liberties.

- ✅ Noto **does** interpret given series of numbers directly as digital audio signal sample magnitudes. _What you see is what you hear._

Sloppy Noto was initially created to produce audio files from the raw datas of various instruments in The [European Space Agency](https://www.esa.int/)'s and The [National Aeronautics and Space Administration](https://nasa.gov)'s space probes. However, Noto can interpret any delimiter-separated values format containing large quantities of numeric data (44100 rows of data = 1 second of audio by default settings).

Suitable file types include (but are not limited to) `.csv`, `.tsv`, `.tab`, `.lst`, `.asc`, `.log`, `.xls`, `.xlsx`, `.json`, `.xml`, `.kml`, `.kmz`. Archive files `.zip`, `.tar`, `.gz` also work as long as there is a single file inside, that is also suitable for Noto to read.

Sloppy Noto runs in [Google Colaboratory](https://colab.research.google.com) (i.e. your browser), using your [Google Drive](https://drive.google.com/drive/my-drive) as data source and/or storage.

You can access the notebook also by using address: https://audiolize.space

## Audio Demos

Audio | Source | Description of converted data | 
------------ | ------------ | ------------- |
[WAV#1](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_xtiito_swvgej.wav) [WAV#2](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_fhurcb_yodazp.wav)| [ESA](https://esa.int) | Grating heater measurements from an ultraviolet imaging spectrograph on [Rosetta](https://en.wikipedia.org/wiki/Rosetta_(spacecraft)). |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_xtiito_yuvkmt.wav)| [ESA](https://esa.int) | Temperature measured by primary mirror sensor of an ultraviolet imaging spectrograph on [Rosetta](https://en.wikipedia.org/wiki/Rosetta_(spacecraft)). |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_bdwqbh_smuwaa.wav)| [ESA](https://esa.int), [JAXA](https://global.jaxa.jp) | Imu Meas SC ang rate Z of AOCS Gyros and IMU on [BepiColombo](https://en.wikipedia.org/wiki/BepiColombo). |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_twflfr_bkezue.wav)  | [ESA](https://esa.int) | Photometric bands of flux-time pairs for given objects, bands and times measuring light curves on [Gaia](https://en.wikipedia.org/wiki/Gaia_(spacecraft)). |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_zzdwul_dixcmw.wav) | [NASA](https://nasa.gov) | Wave electric field intensity data from the Plasma Wave instrument on [Voyager 2](https://en.wikipedia.org/wiki/Voyager_2) from the Jupiter encounter. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_hoqvxl_llofij.wav) | [NASA](https://nasa.gov) | High intensity high energy proton, ion, and electron counting rate from the Energetic Particle experiment on [Voyager 2](https://en.wikipedia.org/wiki/Voyager_2) from the Saturn near encounter. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_lijild_fyvgno.wav)| [HSY](https://hsy.fi) | Air quality from Aeromon BH-12 on [moving trams](https://en.wikipedia.org/wiki/Helsinki_tram_network) in Helsinki. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_wclazy_febwrp.wav)| [FVH](https://forumvirium.fi/) | Water temperatures of several swim beaches in Helsinki. |




## Data Crawlers utility
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/SloppyNoto/blob/master/crawlers.ipynb)

[crawlers.ipynb](https://colab.research.google.com/github/olaviinha/SloppyNoto/blob/master/crawlers.ipynb) is a data crawling utility notebook for finding suitable data file candidates for data to audio conversion from online data archives. It contains an HTTP Crawler, an FTP Crawler and a ZIP Crawler, each listing files recursively from a URL, making educated guesses on what might work, based on file extensions and sizes.

⇨ [Run crawlers.ipynb](https://colab.research.google.com/github/olaviinha/SloppyNoto/blob/master/crawlers.ipynb)

## Some dataset archives to get started
- [ESA Planetary Science Archive](https://archives.esac.esa.int/psa/#!Table%20View)
- [ESAC Science Data Centre](https://www.cosmos.esa.int/web/esdc)
- [NASA Planetary Data System](https://pds.nasa.gov/)
- [NASA Open Data Portal](https://data.nasa.gov/browse)

---

**DO NOT DONATE.** It is illegal for a Finnish citizen to plea for donations, and a donate button placed in the interwebs is interpreted as such plea by the Finnish authorities. Please DO NOT send any donations to [my Paypal](https://paypal.me/oinha) to cover any development related expenses, **especially** if you find these tools useful and want to show support. Use [this Paypal link](https://paypal.me/oinha) for anything but donations. **DO NOT DONATE.**
