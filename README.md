# IMT-542-I3-Lightweight-App
UW MSIM LastFM Visualization

## Goal: 
Build a lightweight (simple) application to visualize LastFM’s top artist charts

## Steps
Create a Readme.md page using markdown to describe the Python application, including how to download, run or use. If the repository is not public, provide the grader and instructor with access to it if possible. 
Feel free to make it as simple or as complex as you would like. 
The goal is to go through the process of using an existing information structure to answer a question or gain an insight. 
Consider building upon your Information Story from G3.

# Method
## LastFM API example:
https://www.last.fm/api/show/chart.getTopArtists
Use LastFM API to get Top Artists 

Their JSON example:
<artists page="1" perPage="50" totalPages="20" total="1000">
  <artist>
    <name>The Beatles</name>
    <playcount>1550293</playcount>
    <listeners>114106</listeners>
    <mbid>b10bbbfc-cf9e-42e0-be17-e2c3e1d2600d</mbid>
    <url>http://www.last.fm/music/The+Beatles</url>
    <streamable>1</streamable>
    <image size="small">http://userserve-ak.last.fm/serve/34/880929.jpg</image>
    <image size="medium">http://userserve-ak.last.fm/serve/64/880929.jpg</image>
    <image size="large">http://userserve-ak.last.fm/serve/126/880929.jpg</image>
    <image size="extralarge">http://userserve-ak.last.fm/serve/252/880929.jpg</image>
    <image size="mega">http://userserve-ak.last.fm/serve/500/880929/The+Beatles.jpg</image>
  </artist>
  ...
</artists>
