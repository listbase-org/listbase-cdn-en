# Music (Music)

16 datasets — 13,097 records

> Browse at [listbase.org/en/music/](https://listbase.org/en/music/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Billboard Hot 100 Songs (1950–2015)](billboard-hot-100-songs.json) | 4,028 | 1150 KB | [CSV](billboard-hot-100-songs_EN.csv) | [Excel](billboard-hot-100-songs_EN.xlsx) | [View](https://listbase.org/en/music/billboard-hot-100-songs/) |
| [Classic Rock Song Play Counts](classic-rock-song-list.json) | 2,229 | 557 KB | [CSV](classic-rock-song-list_EN.csv) | [Excel](classic-rock-song-list_EN.xlsx) | [View](https://listbase.org/en/music/classic-rock-song-list/) |
| [Classic Rock Songs Radio Airplay](classic-rock-songs-radio-airplay.json) | 2,229 | 531 KB | [CSV](classic-rock-songs-radio-airplay_EN.csv) | [Excel](classic-rock-songs-radio-airplay_EN.xlsx) | [View](https://listbase.org/en/music/classic-rock-songs-radio-airplay/) |
| [Guitar Chord Diagrams](guitar-chord-diagrams.json) | 828 | 228 KB | [CSV](guitar-chord-diagrams_EN.csv) | [Excel](guitar-chord-diagrams_EN.xlsx) | [View](https://listbase.org/en/music/guitar-chord-diagrams/) |
| [Top 100 Hit Songs by Decade with Audio Features](top-songs-by-decade-audio-features.json) | 600 | 316 KB | [CSV](top-songs-by-decade-audio-features_EN.csv) | [Excel](top-songs-by-decade-audio-features_EN.xlsx) | [View](https://listbase.org/en/music/top-songs-by-decade-audio-features/) |
| [Skateboarding Video Game Soundtracks](skate-video-game-soundtracks.json) | 568 | 104 KB | [CSV](skate-video-game-soundtracks_EN.csv) | [Excel](skate-video-game-soundtracks_EN.xlsx) | [View](https://listbase.org/en/music/skate-video-game-soundtracks/) |
| [Ukulele Chord Diagrams](ukulele-chord-diagrams.json) | 552 | 122 KB | [CSV](ukulele-chord-diagrams_EN.csv) | [Excel](ukulele-chord-diagrams_EN.xlsx) | [View](https://listbase.org/en/music/ukulele-chord-diagrams/) |
| [Piano Chord Diagrams](piano-chord-diagrams.json) | 528 | 39 KB | [CSV](piano-chord-diagrams_EN.csv) | [Excel](piano-chord-diagrams_EN.xlsx) | [View](https://listbase.org/en/music/piano-chord-diagrams/) |
| [Hip-Hop Songs Mentioning Political Candidates](hip-hop-political-candidate-lyrics.json) | 377 | 134 KB | [CSV](hip-hop-political-candidate-lyrics_EN.csv) | [Excel](hip-hop-political-candidate-lyrics_EN.xlsx) | [View](https://listbase.org/en/music/hip-hop-political-candidate-lyrics/) |
| [Spotify Songs with Audio Features](spotify-songs-audio-features.json) | 350 | 267 KB | [CSV](spotify-songs-audio-features_EN.csv) | [Excel](spotify-songs-audio-features_EN.xlsx) | [View](https://listbase.org/en/music/spotify-songs-audio-features/) |
| [Billboard Top 100 Songs of 2000](billboard-top100-songs-2000.json) | 317 | 66 KB | [CSV](billboard-top100-songs-2000_EN.csv) | [Excel](billboard-top100-songs-2000_EN.xlsx) | [View](https://listbase.org/en/music/billboard-top100-songs-2000/) |
| [Guitar Manufacturers](guitar-manufacturers.json) | 154 | 23 KB | [CSV](guitar-manufacturers_EN.csv) | [Excel](guitar-manufacturers_EN.xlsx) | [View](https://listbase.org/en/music/guitar-manufacturers/) |
| [Popular Names in Songs by Decade](names-in-songs-by-decade.json) | 120 | 15 KB | [CSV](names-in-songs-by-decade_EN.csv) | [Excel](names-in-songs-by-decade_EN.xlsx) | [View](https://listbase.org/en/music/names-in-songs-by-decade/) |
| [Essential Piano Chord Chart Reference Dataset](music-piano-chords.json) | 84 | 22 KB | [CSV](music-piano-chords_EN.csv) | [Excel](music-piano-chords_EN.xlsx) | [View](https://listbase.org/en/music/music-piano-chords/) |
| [Comprehensive Guitar Chord Chart Dataset](music-guitar-chords.json) | 78 | 24 KB | [CSV](music-guitar-chords_EN.csv) | [Excel](music-guitar-chords_EN.xlsx) | [View](https://listbase.org/en/music/music-guitar-chords/) |
| [Musical Instruments](musical-instruments.json) | 55 | 3 KB | [CSV](musical-instruments_EN.csv) | [Excel](musical-instruments_EN.xlsx) | [View](https://listbase.org/en/music/musical-instruments/) |

## Quick Start

```bash
# List all music datasets
curl https://cdn.en.listbase.org/index.json | jq '.datasets[] | select(.category=="music") | .id'

# Fetch a dataset
curl https://cdn.en.listbase.org/music/billboard-hot-100-songs.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/en/music/)
