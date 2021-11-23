---
layout: map
title: Day 24 – Historical map
permalink: /2021/24/
---

This page features the history of many European cities through the centuries, based on [André Ourednik's repository](https://github.com/aourednik/historical-basemaps).

I think I liked the idea of making a non-geographical map for once in this challenge.

Cities' coordinates are fetched from OpenStreetMap Nominatim service, and intersections are computed with countries of every reference year. Few glitches (mostly typos) remained and were manually fixed.

<div id="contribution_day24"></div>
<script type="text/javascript">
    var spec = "https://raw.githubusercontent.com/xoolive/30DayMapChallenge/master/contributions/challenge_day24.json";
    var opt = {"renderer": "canvas", "actions": true};
    vegaEmbed("#contribution_day24", spec, opt).then(function(result) { }).catch(console.error);
</script>
