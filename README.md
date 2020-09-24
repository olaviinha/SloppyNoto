# Sloppy Noto

Sloppy Noto turns data from space probes into raw audio.

While Sloppy Noto can interpret any csv-like data files containing large quantities of numeric data, it was created primarily to produce audio files out of the raw datasets of various space missions by [The European Space Agency](https://www.esa.int/) and [The National Aeronautics and Space Administration](https://nasa.gov). 

**🚫 Noto does not** oscillate or generate sound waves based on given data by other means, modify any such waves, or take artistic freedoms.

**✅ Noto does** interpret given series of numbers directly as digital audio signal sample magnitudes. _What you see is what you hear._

Sloppy Noto runs in [Google Colaboratory](https://colab.research.google.com), using your [Google Drive](https://drive.google.com/drive/my-drive) as data source and/or storage.

## Run Sloppy Noto in Google Colaboratory
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/SloppyNoto/blob/master/sloppyNoto.ipynb)

## Audio Demos

Audio | Source | Description of data used | 
------------ | ------------ | ------------- |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_twflfr_bkezue.wav)  | [ESA](https://esa.int) | Photometric bands of flux-time pairs for given objects, bands and times measuring light curves on Gaia space observatory. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_xtiito_yuvkmt.wav)| [ESA](https://esa.int) | Temperature measured by primary mirror sensor of an ultraviolet imaging spectrograph on Rosetta. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_xtiito_swvgej.wav)| [ESA](https://esa.int) | Unknown measurements from an ultraviolet imaging spectrograph on Rosetta. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_fhurcb_yodazp.wav)| [ESA](https://esa.int) | Unknown measurements from an ultraviolet imaging spectrograph on Rosetta. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_zzdwul_dixcmw.wav) | [NASA](https://nasa.gov) | Wave electric field intensity data from the Plasma Wave instrument on Voyager 2 from the Jupiter encounter. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_hoqvxl_llofij.wav) | [NASA](https://nasa.gov) | High intensity high energy proton, ion, and electron counting rate from the Energetic Particle experiment on Voyager 2 from the Saturn near encounter. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_dcubtb_bozeyk.wav)| [HSY](https://hsy.fi) | Air quality of Helsinki from Aeromon BH-12 on moving trams. |



## FTP crawler utility
As the name suggests, ftp_crawler.ipynb is a utility notebook for finding suitable data file candidates for audio conversion. It lists all files of 5+ MB recursively from a set directory on an FTP server.

#### Run FTP crawler in Google Colaboratory: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/SloppyNoto/blob/master/ftp_crawler.ipynb)

## Some dataset archives to get started
- [ESA Planetary Science Archive](https://archives.esac.esa.int/psa/#!Table%20View)
- [ESAC Science Data Centre](https://www.cosmos.esa.int/web/esdc)
- [NASA Planetary Data System](https://pds.nasa.gov/)
