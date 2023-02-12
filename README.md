# music-text-dataset
This repository lists text sources that can be paired with music (for crawling). Open to contribution.

## Possible Source

| Dataset | Text |
| ------ | ------ |
| [Musicbrainz](https://musicbrainz.org/artist/cc197bad-dc9c-440d-a5b5-d52ba2e14234)| Track, Artist Wikipedia, Track Metadata |
| [Yotube Music Playlist](https://www.youtube.com/watch?v=84YxwrxRc5s) | Title, Description, Tag, Noisy User Comment |
| [AllMusic Review](https://www.allmusic.com/album/abbey-road-mw0000192938) | Album Review |
| [Pitch Fork](https://pitchfork.com/reviews/albums/laraaji-segue-to-infinity/)| Album Review |
| [Song Mearning](https://songmeanings.com/songs/view/3530822107859534370/) | Track Review with Lyrics |
| [FreeSound](https://freesound.org/people/DeVern/sounds/348275/) | Tag, Description |
| [SoundCloud](https://soundcloud.com/moe-p0/newjeans-omg) | Noisy User Comment |
| [Discog](https://www.discogs.com/ko/release/377554-The-Beatles-Let-It-Be) | Noisy User Comment |
| [Juno](https://www.juno.co.uk/products/brightness-shallan-whispers-of-an-ancient-world/920749-01/) | Album Review |
| [Jamendo](https://www.jamendo.com/track/1995659/fade-away-radio-edit) | Track Metadata |

## Current Dataset

### Track-Description Dataset (Sentence)
| Dataset | Text |
| ------ | ------ |
| [MusicCaps](https://huggingface.co/datasets/google/MusicCaps) | describing how the music sounds |

### Track-Description Dataset (Tag)
| Dataset | Text |
| ------ | ------ |
| [MSD-eCALS](https://github.com/seungheondoh/msd-subsets)| Genre,Mood,Style,Theme,Culture + Metadata |
| [Audioset Music](https://research.google.com/audioset/ontology/music_1.html) | Genere,Mood,Style,Instrument |
| [Music4All](https://sites.google.com/view/contact4music4all) | Tag, Lyrics |

### Review Description Dataset
| Dataset | text |
| ------ | ------ |
| [Music4All + Song Meaning](https://zenodo.org/record/6519264) | Track Review |

### Playlist Description Dataset
| Dataset | Text |
| ------ | ------ |
| [Melon Playlist Dataset](https://mtg.github.io/melon-playlist-dataset/) | Playlist Title, Tag |
| [Deezer Playlist Dataset](https://zenodo.org/record/7419490) | Playlist Title |
| [Spotify Million Playlist Dataset](https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge) | Playlist Title |
