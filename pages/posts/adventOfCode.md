---
title: Advent of Code
date: 2022/12/04
description: Advent of Code 2022
tag: puzzles
author: You
---
import Image from 'next/image'

# Advent of Code 2022

<Image
  src="/images/aoc.jpg"
  alt="Advent of Code 2022"
  width={244}
  height={306}
  priority
  className="next-image"
/>

I've been doing AOC for a couple of years now and it's always been a good challenge. This year I've decided to use TypeScript to complete the challenges.

Each day there is a bit of setup work and I've found it annoying and redundant, so I've created a script that handles a lot of it. The <a href="https://github.com/jroxbury/aoc-2022/blob/master/create.js" target="_blank">script</a> will copy over my template directory, update the day based on the cli input, pull the data for that day and open the instructions page.

It's been working out nicely so far and made the experience much more enjoyable. If you want to find out more about my setup or solutions, check out my <a href="https://github.com/jroxbury/aoc-2022" target="_blank">Github repo</a>