# Sloppy Noto

Sloppy Noto turns raw numeric data from space probes into audio.

While Sloppy Noto can interpret any csv-like data files containing large quantities of numeric data, it was created primarily to produce audio files out of the raw datasets of various space missions of [European Space Agency](https://www.esa.int/) and [The National Aeronautics and Space Administration](https://nasa.gov). 

**🚫 Noto does not** oscillate sound, modify any generated sound based on data, take artistc freedoms.

**✅ Noto does** interpret given series of numbers directly as an audio signal. _What you see is what you hear._

Sloppy Noto runs in [Google Colaboratory](https://colab.research.google.com), using your [Google Drive](https://drive.google.com/drive/my-drive) as data source and/or storage.

### Run in Google Colaboratory
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/SloppyNoto/blob/master/sloppyNoto.ipynb)

### Audio Demos

Audio | Source | Converted from data | 
------------ | ------------ | ------------- |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_twflfr_bkezue.wav)  | [ESA](https://esa.int) | Photometric bands of flux-time pairs for given objects, bands and times measuring light curves, from Gaia space observatory. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_zzdwul_dixcmw.wav) | [NASA](https://nasa.gov) | Wave electric field intensity data from the Plasma Wave instrument on Voyager 2 from the Jupiter encounter. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_twflfr_qlyglj.wav)  | [ESA](https://esa.int) | Vega magnitude and band flux value for the transit of flux-time pairs for given objects, bands and times measuring light curves, from Gaia space observatory. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_hoqvxl_llofij.wav) | [NASA](https://nasa.gov) | High intensity high energy proton, ion, and electron counting rate data from the Energetic Particle experiment on Voyager 2 from the Saturn near encounter. |
[WAV](https://storage.googleapis.com/olaviinha/github/sloppy-noto/noto_dcubtb_bozeyk.wav)| [HSY](https://hsy.fi) | Air quality of Helsinki in February 2019, measured using Aeromon BH-12 measurement devices installed on trams. |

### Some dataset archives to get started
- [ESA Planetary Science Archive](https://archives.esac.esa.int/psa/#!Table%20View)
- [ESAC Science Data Centre](https://www.cosmos.esa.int/web/esdc)
- [NASA Planetary Data System](https://pds.nasa.gov/)
