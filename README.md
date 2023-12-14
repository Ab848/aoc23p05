# Day 05
> Time to solve a food production problem by decoding an encoded almanac.

the almanac describes the relationship between:
- seed to soil
- soil to fertilizer
- fertilizer to water
- water to light
- light to temperature
- temperature to humidity
- humidity to location

the almanac starts by list seeds to be planted.
the relationship maps describe how to convert the numbers to and from one another.
the maps are organized as follows:
- [destination range start, source range start, range length]
- destination range start: the first number of the destinationa (i.e. soil in seed to soil)
- source range start: the first number of the source (i.e. seed in seed to soil)
- range: how many numbers in sequential order are in the map

## Tools
- Python
- Vim

## Attribution
[Advent of Code](https://adventofcode.com/2023)
