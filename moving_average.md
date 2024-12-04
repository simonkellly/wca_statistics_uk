## Moving average

*Note: You may think of it as "how well the given person has been doing recently".
      This computes exponentially moving average (EMA) of competitor averages.
      EMA is a weighted average, with weights decreasing exponentially,
      meaning that more recent values contribute more to the computed average.
      Here we use α = 0.8, meaning that the average emphasizes last ~5 results
      (weight of results older than 5 is around 1/3 in total and decreases quickly for particular results).
      People with less than 5 averages are ignored (as there's not much data to base on).*
*Updated on  4 December 2024*


### Rubik's Cube

| Moving average | Person |
| ---: | :--- |
| 6.46 | [James Alonso](https://www.worldcubeassociation.org/persons/2018ALON07) |
| 7.32 | [Nicholas Archer](https://www.worldcubeassociation.org/persons/2020ARCH01) |
| 7.41 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 7.66 | [Johnny Morello Kerlaff](https://www.worldcubeassociation.org/persons/2023KERL01) |
| 7.76 | [Caleb Wolf Dunn](https://www.worldcubeassociation.org/persons/2022DUNN03) |
| 7.79 | [George Scholey](https://www.worldcubeassociation.org/persons/2015SCHO05) |
| 7.95 | [Noah Calderon-Kamata](https://www.worldcubeassociation.org/persons/2022CALD07) |
| 7.98 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 8.04 | [Alan Fang](https://www.worldcubeassociation.org/persons/2023FANG02) |
| 8.06 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 8.26 | [Sean Moran](https://www.worldcubeassociation.org/persons/2016MORA24) |
| 8.29 | [Ryan Chan](https://www.worldcubeassociation.org/persons/2023CHAN16) |
| 8.35 | [Alexander Lau](https://www.worldcubeassociation.org/persons/2011LAUA01) |
| 8.35 | [Tao Yu (喻韬)](https://www.worldcubeassociation.org/persons/2012YUTA01) |
| 8.38 | [Thomas Bevan](https://www.worldcubeassociation.org/persons/2017BEVA01) |
| 8.38 | [Harishan Ramanan](https://www.worldcubeassociation.org/persons/2018RAMA26) |
| 8.40 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 8.41 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 8.48 | [Klyment Diachun](https://www.worldcubeassociation.org/persons/2022DIAC01) |
| 8.58 | [James Tuppenney](https://www.worldcubeassociation.org/persons/2018TUPP02) |
| 8.62 | [Oliver Castledine](https://www.worldcubeassociation.org/persons/2018CAST08) |
| 8.67 | [Rufus Cripps](https://www.worldcubeassociation.org/persons/2022CRIP01) |
| 8.69 | [Felix Hincks](https://www.worldcubeassociation.org/persons/2022HINC01) |
| 8.70 | [Jake Brown](https://www.worldcubeassociation.org/persons/2020BROW01) |
| 8.75 | [Dan Turner](https://www.worldcubeassociation.org/persons/2022TURN10) |
| 8.83 | [Eli Jay](https://www.worldcubeassociation.org/persons/2014JAYE01) |
| 8.83 | [Luke Burns](https://www.worldcubeassociation.org/persons/2020BURN06) |
| 8.84 | [Robert Yau](https://www.worldcubeassociation.org/persons/2009YAUR01) |
| 8.84 | [Jason Harley](https://www.worldcubeassociation.org/persons/2016HARL01) |
| 8.84 | [Monty Fox](https://www.worldcubeassociation.org/persons/2023FOXM01) |
| 8.85 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 8.88 | [Joseph Briggs](https://www.worldcubeassociation.org/persons/2017BRIG03) |
| 8.89 | [Aidan Grainger](https://www.worldcubeassociation.org/persons/2018GRAI01) |
| 8.92 | [Ainesh Sevellaraja](https://www.worldcubeassociation.org/persons/2012SEVE01) |
| 9.03 | [Charlie Harrison](https://www.worldcubeassociation.org/persons/2017HARR08) |
| 9.04 | [Toby Palmer](https://www.worldcubeassociation.org/persons/2022PALM01) |
| 9.05 | [Dean David](https://www.worldcubeassociation.org/persons/2022DAVI06) |
| 9.08 | [Kino Deligero](https://www.worldcubeassociation.org/persons/2018DELI01) |
| 9.09 | [Musa Marsh](https://www.worldcubeassociation.org/persons/2023MARS21) |
| 9.10 | [Daniel Tidsey](https://www.worldcubeassociation.org/persons/2016TIDS01) |
| 9.17 | [Rayan Islam](https://www.worldcubeassociation.org/persons/2022ISLA08) |
| 9.19 | [Bertie Cartwright](https://www.worldcubeassociation.org/persons/2015CART01) |
| 9.23 | [James Airey](https://www.worldcubeassociation.org/persons/2022AIRE02) |
| 9.25 | [Harvie Partridge](https://www.worldcubeassociation.org/persons/2015PART04) |
| 9.27 | [Aayush Sriram Bharadwaj](https://www.worldcubeassociation.org/persons/2018BHAR02) |
| 9.27 | [Luan Philippe Da Silva](https://www.worldcubeassociation.org/persons/2022SILV08) |
| 9.32 | [Adam Black](https://www.worldcubeassociation.org/persons/2022BLAC01) |
| 9.35 | [Katie Moughan](https://www.worldcubeassociation.org/persons/2017DAVI03) |
| 9.37 | [Stephen Waller](https://www.worldcubeassociation.org/persons/2017WALL12) |
| 9.38 | [Harvey John Walton](https://www.worldcubeassociation.org/persons/2019WALT06) |

### 2x2x2 Cube

| Moving average | Person |
| ---: | :--- |
| 1.51 | [James Alonso](https://www.worldcubeassociation.org/persons/2018ALON07) |
| 1.81 | [Luke Burns](https://www.worldcubeassociation.org/persons/2020BURN06) |
| 1.82 | [Dan Turner](https://www.worldcubeassociation.org/persons/2022TURN10) |
| 1.83 | [Max Tully](https://www.worldcubeassociation.org/persons/2023TULL04) |
| 1.84 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 1.91 | [Harry Allen](https://www.worldcubeassociation.org/persons/2023ALLE01) |
| 1.97 | [Noah Calderon-Kamata](https://www.worldcubeassociation.org/persons/2022CALD07) |
| 2.16 | [Nicky Sim](https://www.worldcubeassociation.org/persons/2022SIMN02) |
| 2.16 | [Alan Fang](https://www.worldcubeassociation.org/persons/2023FANG02) |
| 2.17 | [Nicholas Archer](https://www.worldcubeassociation.org/persons/2020ARCH01) |
| 2.21 | [George Scholey](https://www.worldcubeassociation.org/persons/2015SCHO05) |
| 2.23 | [Joshua Da Costa](https://www.worldcubeassociation.org/persons/2022COST18) |
| 2.35 | [Johnny Morello Kerlaff](https://www.worldcubeassociation.org/persons/2023KERL01) |
| 2.40 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 2.41 | [Fabio Rossi](https://www.worldcubeassociation.org/persons/2022ROSS02) |
| 2.43 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 2.44 | [Ryan Chan](https://www.worldcubeassociation.org/persons/2023CHAN16) |
| 2.45 | [Daniel Robinson](https://www.worldcubeassociation.org/persons/2023ROBI10) |
| 2.57 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 2.58 | [Ainesh Sevellaraja](https://www.worldcubeassociation.org/persons/2012SEVE01) |
| 2.60 | [Anqi Yu](https://www.worldcubeassociation.org/persons/2018YUAN02) |
| 2.60 | [Satya Bhavesh Gala](https://www.worldcubeassociation.org/persons/2022GALA03) |
| 2.62 | [Caleb Wolf Dunn](https://www.worldcubeassociation.org/persons/2022DUNN03) |
| 2.68 | [Aayush Sriram Bharadwaj](https://www.worldcubeassociation.org/persons/2018BHAR02) |
| 2.74 | [Harishan Ramanan](https://www.worldcubeassociation.org/persons/2018RAMA26) |
| 2.75 | [James Tuppenney](https://www.worldcubeassociation.org/persons/2018TUPP02) |
| 2.78 | [Aidan Grainger](https://www.worldcubeassociation.org/persons/2018GRAI01) |
| 2.84 | [Jaye Sloan](https://www.worldcubeassociation.org/persons/2022SLOA01) |
| 2.85 | [Murad Asgarov](https://www.worldcubeassociation.org/persons/2022ASGA01) |
| 2.85 | [Daniel Chiu](https://www.worldcubeassociation.org/persons/2022CHIU06) |
| 2.86 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 2.98 | [Amaan Omar](https://www.worldcubeassociation.org/persons/2016OMAR01) |
| 3.03 | [Kris Lim](https://www.worldcubeassociation.org/persons/2022LIMK01) |
| 3.04 | [Lewis Byng](https://www.worldcubeassociation.org/persons/2015BYNG02) |
| 3.04 | [Jake Brown](https://www.worldcubeassociation.org/persons/2020BROW01) |
| 3.08 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 3.09 | [Daniel Tidsey](https://www.worldcubeassociation.org/persons/2016TIDS01) |
| 3.09 | [Albie Cooper](https://www.worldcubeassociation.org/persons/2022COOP04) |
| 3.11 | [Luan Philippe Da Silva](https://www.worldcubeassociation.org/persons/2022SILV08) |
| 3.13 | [Naglis Peciulis](https://www.worldcubeassociation.org/persons/2017PECI01) |
| 3.13 | [Kai Roff](https://www.worldcubeassociation.org/persons/2018ROFF01) |
| 3.15 | [Monty Fox](https://www.worldcubeassociation.org/persons/2023FOXM01) |
| 3.16 | [Ben Whitmore](https://www.worldcubeassociation.org/persons/2009WHIT01) |
| 3.17 | [Isaac Corker](https://www.worldcubeassociation.org/persons/2024CORK01) |
| 3.18 | [Bella Campbell](https://www.worldcubeassociation.org/persons/2018CAMP17) |
| 3.18 | [Jacob Sherwen Brown](https://www.worldcubeassociation.org/persons/2022BROW01) |
| 3.24 | [Felix Hincks](https://www.worldcubeassociation.org/persons/2022HINC01) |
| 3.26 | [Oscar Bickmore](https://www.worldcubeassociation.org/persons/2023BICK01) |
| 3.36 | [Jaidon Adams](https://www.worldcubeassociation.org/persons/2018ADAM11) |
| 3.37 | [Billie Hammill](https://www.worldcubeassociation.org/persons/2015HAMM01) |

### 4x4x4 Cube

| Moving average | Person |
| ---: | :--- |
| 28.11 | [Dean David](https://www.worldcubeassociation.org/persons/2022DAVI06) |
| 30.49 | [Eli Jay](https://www.worldcubeassociation.org/persons/2014JAYE01) |
| 30.65 | [Harishan Ramanan](https://www.worldcubeassociation.org/persons/2018RAMA26) |
| 30.72 | [Harvie Partridge](https://www.worldcubeassociation.org/persons/2015PART04) |
| 30.95 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 31.50 | [Robert Yau](https://www.worldcubeassociation.org/persons/2009YAUR01) |
| 31.52 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 31.76 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 31.78 | [Daniel Chiu](https://www.worldcubeassociation.org/persons/2022CHIU06) |
| 31.94 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 32.44 | [Sean Moran](https://www.worldcubeassociation.org/persons/2016MORA24) |
| 32.58 | [Nicholas Archer](https://www.worldcubeassociation.org/persons/2020ARCH01) |
| 32.59 | [Harry Dixon](https://www.worldcubeassociation.org/persons/2023DIXO02) |
| 32.64 | [George Scholey](https://www.worldcubeassociation.org/persons/2015SCHO05) |
| 32.75 | [Ryan Chan](https://www.worldcubeassociation.org/persons/2023CHAN16) |
| 32.78 | [Noah Calderon-Kamata](https://www.worldcubeassociation.org/persons/2022CALD07) |
| 33.31 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 33.49 | [Ainesh Sevellaraja](https://www.worldcubeassociation.org/persons/2012SEVE01) |
| 34.24 | [Caleb Wolf Dunn](https://www.worldcubeassociation.org/persons/2022DUNN03) |
| 34.44 | [James Alonso](https://www.worldcubeassociation.org/persons/2018ALON07) |
| 34.56 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 34.63 | [Naglis Peciulis](https://www.worldcubeassociation.org/persons/2017PECI01) |
| 34.66 | [Brandon Poulton](https://www.worldcubeassociation.org/persons/2019POUL02) |
| 34.67 | [Ziang Yan (晏子昂)](https://www.worldcubeassociation.org/persons/2017YANZ01) |
| 34.75 | [Alan Fang](https://www.worldcubeassociation.org/persons/2023FANG02) |
| 34.78 | [Max Kwok U Sam (郭愉琛)](https://www.worldcubeassociation.org/persons/2018SAMK01) |
| 34.88 | [Sameer Mahmood](https://www.worldcubeassociation.org/persons/2013MAHM02) |
| 34.95 | [Katie Moughan](https://www.worldcubeassociation.org/persons/2017DAVI03) |
| 35.17 | [Sam Jacklin](https://www.worldcubeassociation.org/persons/2015JACK04) |
| 35.22 | [Matthew Lowe](https://www.worldcubeassociation.org/persons/2014LOWE01) |
| 35.56 | [Thomas Bevan](https://www.worldcubeassociation.org/persons/2017BEVA01) |
| 35.66 | [Charlie Harrison](https://www.worldcubeassociation.org/persons/2017HARR08) |
| 35.77 | [Billie Hammill](https://www.worldcubeassociation.org/persons/2015HAMM01) |
| 35.88 | [Monty Fox](https://www.worldcubeassociation.org/persons/2023FOXM01) |
| 35.95 | [Aidan Grainger](https://www.worldcubeassociation.org/persons/2018GRAI01) |
| 36.09 | [Oliver Castledine](https://www.worldcubeassociation.org/persons/2018CAST08) |
| 36.34 | [Murad Asgarov](https://www.worldcubeassociation.org/persons/2022ASGA01) |
| 36.38 | [Luke Burns](https://www.worldcubeassociation.org/persons/2020BURN06) |
| 36.76 | [Edward Nutter](https://www.worldcubeassociation.org/persons/2018NUTT01) |
| 36.98 | [Dan Turner](https://www.worldcubeassociation.org/persons/2022TURN10) |
| 37.02 | [Adam Black](https://www.worldcubeassociation.org/persons/2022BLAC01) |
| 37.12 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 37.34 | [Tan Jun (陈俊)](https://www.worldcubeassociation.org/persons/2018JUNT01) |
| 37.46 | [Jake Brown](https://www.worldcubeassociation.org/persons/2020BROW01) |
| 38.33 | [Felix Hincks](https://www.worldcubeassociation.org/persons/2022HINC01) |
| 38.58 | [Callum Hales-Jepp](https://www.worldcubeassociation.org/persons/2012HALE01) |
| 38.60 | [Stephen Waller](https://www.worldcubeassociation.org/persons/2017WALL12) |
| 38.76 | [Toby Palmer](https://www.worldcubeassociation.org/persons/2022PALM01) |
| 38.81 | [Steven Kearns](https://www.worldcubeassociation.org/persons/2015KEAR01) |
| 39.04 | [Daniel Sheppard](https://www.worldcubeassociation.org/persons/2009SHEP01) |

### 5x5x5 Cube

| Moving average | Person |
| ---: | :--- |
| 50.15 | [Eli Jay](https://www.worldcubeassociation.org/persons/2014JAYE01) |
| 51.27 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 53.72 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 54.52 | [Dean David](https://www.worldcubeassociation.org/persons/2022DAVI06) |
| 54.63 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 55.37 | [Jake Brown](https://www.worldcubeassociation.org/persons/2020BROW01) |
| 56.76 | [Max Kwok U Sam (郭愉琛)](https://www.worldcubeassociation.org/persons/2018SAMK01) |
| 58.47 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 59.41 | [Robert Yau](https://www.worldcubeassociation.org/persons/2009YAUR01) |
| 59.58 | [Sean Moran](https://www.worldcubeassociation.org/persons/2016MORA24) |
| 1:01.03 | [Nicholas Archer](https://www.worldcubeassociation.org/persons/2020ARCH01) |
| 1:01.20 | [George Scholey](https://www.worldcubeassociation.org/persons/2015SCHO05) |
| 1:01.48 | [Alan Fang](https://www.worldcubeassociation.org/persons/2023FANG02) |
| 1:01.71 | [Harvie Partridge](https://www.worldcubeassociation.org/persons/2015PART04) |
| 1:02.15 | [Katie Moughan](https://www.worldcubeassociation.org/persons/2017DAVI03) |
| 1:02.69 | [Caleb Wolf Dunn](https://www.worldcubeassociation.org/persons/2022DUNN03) |
| 1:02.81 | [Ainesh Sevellaraja](https://www.worldcubeassociation.org/persons/2012SEVE01) |
| 1:02.97 | [Daniel Chiu](https://www.worldcubeassociation.org/persons/2022CHIU06) |
| 1:03.50 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 1:03.60 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 1:03.70 | [Daniel Evans](https://www.worldcubeassociation.org/persons/2016EVAN06) |
| 1:04.18 | [Monty Fox](https://www.worldcubeassociation.org/persons/2023FOXM01) |
| 1:04.22 | [Tan Jun (陈俊)](https://www.worldcubeassociation.org/persons/2018JUNT01) |
| 1:04.29 | [Sam Jacklin](https://www.worldcubeassociation.org/persons/2015JACK04) |
| 1:04.61 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 1:04.69 | [Brandon Poulton](https://www.worldcubeassociation.org/persons/2019POUL02) |
| 1:05.08 | [Noah Calderon-Kamata](https://www.worldcubeassociation.org/persons/2022CALD07) |
| 1:05.56 | [Breandan Vallance](https://www.worldcubeassociation.org/persons/2007VALL01) |
| 1:06.02 | [Harishan Ramanan](https://www.worldcubeassociation.org/persons/2018RAMA26) |
| 1:06.58 | [Oliver Castledine](https://www.worldcubeassociation.org/persons/2018CAST08) |
| 1:06.75 | [Naglis Peciulis](https://www.worldcubeassociation.org/persons/2017PECI01) |
| 1:06.82 | [Mark Ostrom](https://www.worldcubeassociation.org/persons/2017OSTR01) |
| 1:07.23 | [Aidan Grainger](https://www.worldcubeassociation.org/persons/2018GRAI01) |
| 1:07.24 | [Ziang Yan (晏子昂)](https://www.worldcubeassociation.org/persons/2017YANZ01) |
| 1:07.85 | [Christopher Morris](https://www.worldcubeassociation.org/persons/2013MORR03) |
| 1:07.92 | [Sameer Mahmood](https://www.worldcubeassociation.org/persons/2013MAHM02) |
| 1:08.01 | [Adam Black](https://www.worldcubeassociation.org/persons/2022BLAC01) |
| 1:08.19 | [Jason Harley](https://www.worldcubeassociation.org/persons/2016HARL01) |
| 1:08.99 | [Luke Burns](https://www.worldcubeassociation.org/persons/2020BURN06) |
| 1:09.38 | [Dan Turner](https://www.worldcubeassociation.org/persons/2022TURN10) |
| 1:09.86 | [Marcus Siu](https://www.worldcubeassociation.org/persons/2016SIUM01) |
| 1:10.35 | [Ryan Chan](https://www.worldcubeassociation.org/persons/2023CHAN16) |
| 1:10.55 | [Daniel Sheppard](https://www.worldcubeassociation.org/persons/2009SHEP01) |
| 1:11.10 | [Sam Shaw](https://www.worldcubeassociation.org/persons/2016SHAW02) |
| 1:11.26 | [Aidan McMillan](https://www.worldcubeassociation.org/persons/2018MCMI02) |
| 1:11.32 | [Murad Asgarov](https://www.worldcubeassociation.org/persons/2022ASGA01) |
| 1:11.33 | [Cormac Farrell](https://www.worldcubeassociation.org/persons/2016FARR01) |
| 1:11.57 | [Samaran Natarajan](https://www.worldcubeassociation.org/persons/2019NATA01) |
| 1:11.78 | [Callum Hales-Jepp](https://www.worldcubeassociation.org/persons/2012HALE01) |
| 1:11.81 | [Stephen Waller](https://www.worldcubeassociation.org/persons/2017WALL12) |

### 6x6x6 Cube

| Moving average | Person |
| ---: | :--- |
| 1:32.86 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 1:33.56 | [Eli Jay](https://www.worldcubeassociation.org/persons/2014JAYE01) |
| 1:37.85 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 1:44.96 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 1:48.64 | [Dean David](https://www.worldcubeassociation.org/persons/2022DAVI06) |
| 1:52.23 | [Daniel Evans](https://www.worldcubeassociation.org/persons/2016EVAN06) |
| 1:53.09 | [Robert Yau](https://www.worldcubeassociation.org/persons/2009YAUR01) |
| 1:53.17 | [Mark Ostrom](https://www.worldcubeassociation.org/persons/2017OSTR01) |
| 1:53.59 | [Max Kwok U Sam (郭愉琛)](https://www.worldcubeassociation.org/persons/2018SAMK01) |
| 1:54.14 | [Sean Moran](https://www.worldcubeassociation.org/persons/2016MORA24) |
| 1:54.81 | [Jake Brown](https://www.worldcubeassociation.org/persons/2020BROW01) |
| 1:54.84 | [Katie Moughan](https://www.worldcubeassociation.org/persons/2017DAVI03) |
| 1:56.19 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 1:57.86 | [Jason Harley](https://www.worldcubeassociation.org/persons/2016HARL01) |
| 1:58.79 | [Steven Kearns](https://www.worldcubeassociation.org/persons/2015KEAR01) |
| 2:01.00 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 2:01.49 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 2:02.68 | [Harvie Partridge](https://www.worldcubeassociation.org/persons/2015PART04) |
| 2:03.85 | [Ainesh Sevellaraja](https://www.worldcubeassociation.org/persons/2012SEVE01) |
| 2:05.43 | [Tan Jun (陈俊)](https://www.worldcubeassociation.org/persons/2018JUNT01) |
| 2:08.10 | [Oliver Castledine](https://www.worldcubeassociation.org/persons/2018CAST08) |
| 2:08.40 | [Sam Jacklin](https://www.worldcubeassociation.org/persons/2015JACK04) |
| 2:08.80 | [Sam Shaw](https://www.worldcubeassociation.org/persons/2016SHAW02) |
| 2:09.52 | [Noah Calderon-Kamata](https://www.worldcubeassociation.org/persons/2022CALD07) |
| 2:10.93 | [Monty Fox](https://www.worldcubeassociation.org/persons/2023FOXM01) |
| 2:11.12 | [Aidan Grainger](https://www.worldcubeassociation.org/persons/2018GRAI01) |
| 2:11.37 | [Adam Black](https://www.worldcubeassociation.org/persons/2022BLAC01) |
| 2:12.09 | [Christopher Morris](https://www.worldcubeassociation.org/persons/2013MORR03) |
| 2:12.86 | [James Molloy](https://www.worldcubeassociation.org/persons/2011MOLL01) |
| 2:13.49 | [William Cadwell Walker](https://www.worldcubeassociation.org/persons/2022WALK02) |
| 2:13.93 | [Marcus Siu](https://www.worldcubeassociation.org/persons/2016SIUM01) |
| 2:14.10 | [Breandan Vallance](https://www.worldcubeassociation.org/persons/2007VALL01) |
| 2:14.49 | [James Ballantine](https://www.worldcubeassociation.org/persons/2018BALL01) |
| 2:14.66 | [Ryan Chan](https://www.worldcubeassociation.org/persons/2023CHAN16) |
| 2:14.79 | [Sameer Mahmood](https://www.worldcubeassociation.org/persons/2013MAHM02) |
| 2:15.33 | [Joe Ewbank](https://www.worldcubeassociation.org/persons/2015EWBA01) |
| 2:16.07 | [Callum Hales-Jepp](https://www.worldcubeassociation.org/persons/2012HALE01) |
| 2:16.64 | [Matthew Stephenson](https://www.worldcubeassociation.org/persons/2022STEP04) |
| 2:17.30 | [Brandon Poulton](https://www.worldcubeassociation.org/persons/2019POUL02) |
| 2:17.74 | [Bella Campbell](https://www.worldcubeassociation.org/persons/2018CAMP17) |
| 2:18.39 | [George Scholey](https://www.worldcubeassociation.org/persons/2015SCHO05) |
| 2:18.81 | [Nevins Chan Pak Hoong (陈百鸿)](https://www.worldcubeassociation.org/persons/2010CHAN20) |
| 2:19.73 | [Daniel Sheppard](https://www.worldcubeassociation.org/persons/2009SHEP01) |
| 2:20.13 | [Oliver Richards](https://www.worldcubeassociation.org/persons/2022RICH02) |
| 2:20.34 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 2:21.50 | [Naglis Peciulis](https://www.worldcubeassociation.org/persons/2017PECI01) |
| 2:22.51 | [Christopher Kilgallon](https://www.worldcubeassociation.org/persons/2022KILG02) |
| 2:23.20 | [Jonathan Pugsley](https://www.worldcubeassociation.org/persons/2018PUGS01) |
| 2:23.24 | [Hazel Hughes](https://www.worldcubeassociation.org/persons/2015HUGH04) |
| 2:23.63 | [Ziang Yan (晏子昂)](https://www.worldcubeassociation.org/persons/2017YANZ01) |

### 7x7x7 Cube

| Moving average | Person |
| ---: | :--- |
| 2:23.55 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 2:23.62 | [Eli Jay](https://www.worldcubeassociation.org/persons/2014JAYE01) |
| 2:32.31 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 2:42.81 | [Mark Ostrom](https://www.worldcubeassociation.org/persons/2017OSTR01) |
| 2:44.02 | [Daniel Evans](https://www.worldcubeassociation.org/persons/2016EVAN06) |
| 2:45.16 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 2:53.28 | [Max Kwok U Sam (郭愉琛)](https://www.worldcubeassociation.org/persons/2018SAMK01) |
| 2:54.74 | [Katie Moughan](https://www.worldcubeassociation.org/persons/2017DAVI03) |
| 2:54.77 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 2:55.11 | [Jason Harley](https://www.worldcubeassociation.org/persons/2016HARL01) |
| 2:55.45 | [Sean Moran](https://www.worldcubeassociation.org/persons/2016MORA24) |
| 3:00.33 | [Steven Kearns](https://www.worldcubeassociation.org/persons/2015KEAR01) |
| 3:03.11 | [Robert Yau](https://www.worldcubeassociation.org/persons/2009YAUR01) |
| 3:03.39 | [Jake Brown](https://www.worldcubeassociation.org/persons/2020BROW01) |
| 3:05.27 | [Sam Jacklin](https://www.worldcubeassociation.org/persons/2015JACK04) |
| 3:10.45 | [Dean David](https://www.worldcubeassociation.org/persons/2022DAVI06) |
| 3:11.61 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 3:13.70 | [Tan Jun (陈俊)](https://www.worldcubeassociation.org/persons/2018JUNT01) |
| 3:14.62 | [William Cadwell Walker](https://www.worldcubeassociation.org/persons/2022WALK02) |
| 3:14.67 | [Daniel Sheppard](https://www.worldcubeassociation.org/persons/2009SHEP01) |
| 3:14.70 | [Sameer Mahmood](https://www.worldcubeassociation.org/persons/2013MAHM02) |
| 3:16.94 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 3:18.05 | [Christopher Morris](https://www.worldcubeassociation.org/persons/2013MORR03) |
| 3:18.42 | [Breandan Vallance](https://www.worldcubeassociation.org/persons/2007VALL01) |
| 3:20.31 | [Sam Shaw](https://www.worldcubeassociation.org/persons/2016SHAW02) |
| 3:20.60 | [Brandon Poulton](https://www.worldcubeassociation.org/persons/2019POUL02) |
| 3:21.88 | [Ainesh Sevellaraja](https://www.worldcubeassociation.org/persons/2012SEVE01) |
| 3:24.10 | [Callum Hales-Jepp](https://www.worldcubeassociation.org/persons/2012HALE01) |
| 3:24.48 | [Adam Black](https://www.worldcubeassociation.org/persons/2022BLAC01) |
| 3:24.65 | [Marcus Siu](https://www.worldcubeassociation.org/persons/2016SIUM01) |
| 3:24.86 | [Harvie Partridge](https://www.worldcubeassociation.org/persons/2015PART04) |
| 3:25.07 | [James Molloy](https://www.worldcubeassociation.org/persons/2011MOLL01) |
| 3:25.83 | [Oliver Castledine](https://www.worldcubeassociation.org/persons/2018CAST08) |
| 3:28.82 | [Joe Ewbank](https://www.worldcubeassociation.org/persons/2015EWBA01) |
| 3:30.15 | [Nevins Chan Pak Hoong (陈百鸿)](https://www.worldcubeassociation.org/persons/2010CHAN20) |
| 3:31.37 | [Noah Calderon-Kamata](https://www.worldcubeassociation.org/persons/2022CALD07) |
| 3:33.50 | [James Ballantine](https://www.worldcubeassociation.org/persons/2018BALL01) |
| 3:33.82 | [Jonathan Pugsley](https://www.worldcubeassociation.org/persons/2018PUGS01) |
| 3:36.03 | [Bella Campbell](https://www.worldcubeassociation.org/persons/2018CAMP17) |
| 3:37.02 | [Oliver Richards](https://www.worldcubeassociation.org/persons/2022RICH02) |
| 3:40.15 | [Matthew Stephenson](https://www.worldcubeassociation.org/persons/2022STEP04) |
| 3:40.48 | [Aidan Grainger](https://www.worldcubeassociation.org/persons/2018GRAI01) |
| 3:41.82 | [Murad Asgarov](https://www.worldcubeassociation.org/persons/2022ASGA01) |
| 3:43.24 | [Cormac Farrell](https://www.worldcubeassociation.org/persons/2016FARR01) |
| 3:43.86 | [Christopher Kilgallon](https://www.worldcubeassociation.org/persons/2022KILG02) |
| 3:44.87 | [Harry Taylor](https://www.worldcubeassociation.org/persons/2014TAYL06) |
| 3:45.72 | [Toby Sainthouse](https://www.worldcubeassociation.org/persons/2016SAIN04) |
| 3:47.82 | [Fengyuan Kelvin Lou (楼丰源)](https://www.worldcubeassociation.org/persons/2023LOUF01) |
| 3:47.94 | [Hazel Hughes](https://www.worldcubeassociation.org/persons/2015HUGH04) |
| 3:49.84 | [Aidan McMillan](https://www.worldcubeassociation.org/persons/2018MCMI02) |

### 3x3x3 Fewest Moves

| Moving average | Person |
| ---: | :--- |
| 23.19 | [Jaye Sloan](https://www.worldcubeassociation.org/persons/2022SLOA01) |
| 23.65 | [Kai Cui](https://www.worldcubeassociation.org/persons/2019CUIK03) |
| 24.29 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 24.65 | [Lichi Fang (方力驰)](https://www.worldcubeassociation.org/persons/2018FANG03) |
| 25.79 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 26.70 | [Daniel Sheppard](https://www.worldcubeassociation.org/persons/2009SHEP01) |
| 28.88 | [Karam Al-Robaie](https://www.worldcubeassociation.org/persons/2016ALRO01) |
| 29.19 | [Robert Yau](https://www.worldcubeassociation.org/persons/2009YAUR01) |
| 29.88 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 30.73 | [Ben Coppin](https://www.worldcubeassociation.org/persons/2013COPP01) |
| 31.09 | [Eli Jay](https://www.worldcubeassociation.org/persons/2014JAYE01) |
| 31.16 | [Ainesh Sevellaraja](https://www.worldcubeassociation.org/persons/2012SEVE01) |
| 31.35 | [Jason Harley](https://www.worldcubeassociation.org/persons/2016HARL01) |
| 33.08 | [Dorian Chan](https://www.worldcubeassociation.org/persons/2023DORI01) |
| 33.09 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 33.30 | [Harry Owen](https://www.worldcubeassociation.org/persons/2017OWEN01) |
| 33.33 | [Jake Brown](https://www.worldcubeassociation.org/persons/2020BROW01) |
| 33.38 | [James Molloy](https://www.worldcubeassociation.org/persons/2011MOLL01) |
| 33.41 | [Charlie Stark](https://www.worldcubeassociation.org/persons/2014STAR05) |
| 33.97 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 34.13 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 34.18 | [Oliver Wheat](https://www.worldcubeassociation.org/persons/2016WHEA01) |
| 34.36 | [Ben Whitmore](https://www.worldcubeassociation.org/persons/2009WHIT01) |
| 34.39 | [Sean Moran](https://www.worldcubeassociation.org/persons/2016MORA24) |
| 34.42 | [Callum Hales-Jepp](https://www.worldcubeassociation.org/persons/2012HALE01) |
| 35.33 | [Bella Campbell](https://www.worldcubeassociation.org/persons/2018CAMP17) |
| 35.83 | [Billie Hammill](https://www.worldcubeassociation.org/persons/2015HAMM01) |
| 35.96 | [Anqi Yu](https://www.worldcubeassociation.org/persons/2018YUAN02) |
| 36.95 | [Callum James Goodyear-Jørgensen](https://www.worldcubeassociation.org/persons/2012GOOD02) |
| 38.01 | [Mengfei Shen (沈梦非)](https://www.worldcubeassociation.org/persons/2018SHEN07) |
| 38.02 | [Sam Shaw](https://www.worldcubeassociation.org/persons/2016SHAW02) |
| 40.25 | [Ashwyn Wadhawan](https://www.worldcubeassociation.org/persons/2022WADH02) |
| 40.40 | [Adam Devere](https://www.worldcubeassociation.org/persons/2018DEVE02) |
| 43.86 | [Nevins Chan Pak Hoong (陈百鸿)](https://www.worldcubeassociation.org/persons/2010CHAN20) |
| 46.57 | [AJ Nicholls](https://www.worldcubeassociation.org/persons/2015NICH04) |
| 46.76 | [Ryan Eckersley](https://www.worldcubeassociation.org/persons/2019ECKE02) |

### 3x3x3 One-Handed

| Moving average | Person |
| ---: | :--- |
| 9.15 | [Nicholas Archer](https://www.worldcubeassociation.org/persons/2020ARCH01) |
| 11.55 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 11.80 | [Louis de Mendonça](https://www.worldcubeassociation.org/persons/2013MEND03) |
| 12.05 | [Tao Yu (喻韬)](https://www.worldcubeassociation.org/persons/2012YUTA01) |
| 12.99 | [Joseph Briggs](https://www.worldcubeassociation.org/persons/2017BRIG03) |
| 13.04 | [Johnny Morello Kerlaff](https://www.worldcubeassociation.org/persons/2023KERL01) |
| 13.75 | [Sean Moran](https://www.worldcubeassociation.org/persons/2016MORA24) |
| 13.82 | [George Scholey](https://www.worldcubeassociation.org/persons/2015SCHO05) |
| 13.95 | [Alan Fang](https://www.worldcubeassociation.org/persons/2023FANG02) |
| 14.09 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 14.32 | [Robert Yau](https://www.worldcubeassociation.org/persons/2009YAUR01) |
| 14.58 | [James Alonso](https://www.worldcubeassociation.org/persons/2018ALON07) |
| 15.10 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 15.18 | [Noah Calderon-Kamata](https://www.worldcubeassociation.org/persons/2022CALD07) |
| 15.24 | [Dan Turner](https://www.worldcubeassociation.org/persons/2022TURN10) |
| 15.52 | [Caleb Wolf Dunn](https://www.worldcubeassociation.org/persons/2022DUNN03) |
| 15.66 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 15.71 | [Stephen Waller](https://www.worldcubeassociation.org/persons/2017WALL12) |
| 15.72 | [Luan Philippe Da Silva](https://www.worldcubeassociation.org/persons/2022SILV08) |
| 15.79 | [Ivo Morley](https://www.worldcubeassociation.org/persons/2024MORL01) |
| 15.80 | [Max Kwok U Sam (郭愉琛)](https://www.worldcubeassociation.org/persons/2018SAMK01) |
| 15.81 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 15.95 | [Sameer Mahmood](https://www.worldcubeassociation.org/persons/2013MAHM02) |
| 15.96 | [Ainesh Sevellaraja](https://www.worldcubeassociation.org/persons/2012SEVE01) |
| 16.01 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 16.02 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 16.20 | [Alexander Yip](https://www.worldcubeassociation.org/persons/2015YIPA01) |
| 16.24 | [Oliver Castledine](https://www.worldcubeassociation.org/persons/2018CAST08) |
| 16.37 | [Tom Salmon](https://www.worldcubeassociation.org/persons/2015SALM03) |
| 16.60 | [Marcus Siu](https://www.worldcubeassociation.org/persons/2016SIUM01) |
| 16.65 | [Monty Fox](https://www.worldcubeassociation.org/persons/2023FOXM01) |
| 16.70 | [Dean David](https://www.worldcubeassociation.org/persons/2022DAVI06) |
| 16.90 | [Adam Devere](https://www.worldcubeassociation.org/persons/2018DEVE02) |
| 16.93 | [Alexander Lau](https://www.worldcubeassociation.org/persons/2011LAUA01) |
| 17.05 | [Josh Newton](https://www.worldcubeassociation.org/persons/2019NEWT02) |
| 17.17 | [Rufus Cripps](https://www.worldcubeassociation.org/persons/2022CRIP01) |
| 17.18 | [Aarin Manik](https://www.worldcubeassociation.org/persons/2017MANI03) |
| 17.34 | [Fengyuan Kelvin Lou (楼丰源)](https://www.worldcubeassociation.org/persons/2023LOUF01) |
| 17.38 | [Thomas Bevan](https://www.worldcubeassociation.org/persons/2017BEVA01) |
| 17.43 | [Matthew Stephenson](https://www.worldcubeassociation.org/persons/2022STEP04) |
| 17.45 | [Hussain Iqbal](https://www.worldcubeassociation.org/persons/2016IQBA01) |
| 17.55 | [Daniel Chiu](https://www.worldcubeassociation.org/persons/2022CHIU06) |
| 17.55 | [Ryan Chan](https://www.worldcubeassociation.org/persons/2023CHAN16) |
| 17.56 | [Joe Ewbank](https://www.worldcubeassociation.org/persons/2015EWBA01) |
| 17.80 | [Milo Taylor](https://www.worldcubeassociation.org/persons/2018TAYL22) |
| 17.83 | [Callum Hales-Jepp](https://www.worldcubeassociation.org/persons/2012HALE01) |
| 17.87 | [Finley Norris](https://www.worldcubeassociation.org/persons/2022NORR01) |
| 18.04 | [Dominic Lumsden](https://www.worldcubeassociation.org/persons/2016LUMS01) |
| 18.04 | [Toby Palmer](https://www.worldcubeassociation.org/persons/2022PALM01) |
| 18.05 | [Aidan Grainger](https://www.worldcubeassociation.org/persons/2018GRAI01) |

### Megaminx

| Moving average | Person |
| ---: | :--- |
| 30.70 | [Aidan Grainger](https://www.worldcubeassociation.org/persons/2018GRAI01) |
| 32.76 | [Sean Moran](https://www.worldcubeassociation.org/persons/2016MORA24) |
| 40.45 | [Katie Moughan](https://www.worldcubeassociation.org/persons/2017DAVI03) |
| 40.98 | [Oliver Richards](https://www.worldcubeassociation.org/persons/2022RICH02) |
| 45.09 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 45.20 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 46.15 | [Ainesh Sevellaraja](https://www.worldcubeassociation.org/persons/2012SEVE01) |
| 46.84 | [Sophie Gilbert](https://www.worldcubeassociation.org/persons/2022GILB05) |
| 47.13 | [Finley Norris](https://www.worldcubeassociation.org/persons/2022NORR01) |
| 47.27 | [Matthew Stephenson](https://www.worldcubeassociation.org/persons/2022STEP04) |
| 48.52 | [Eli Jay](https://www.worldcubeassociation.org/persons/2014JAYE01) |
| 48.90 | [Fred Lang](https://www.worldcubeassociation.org/persons/2016LANG12) |
| 49.29 | [Caleb Wolf Dunn](https://www.worldcubeassociation.org/persons/2022DUNN03) |
| 49.30 | [Stephen Waller](https://www.worldcubeassociation.org/persons/2017WALL12) |
| 49.65 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 50.03 | [Sarah Durling](https://www.worldcubeassociation.org/persons/2022DURL01) |
| 50.51 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 50.59 | [Cormac Farrell](https://www.worldcubeassociation.org/persons/2016FARR01) |
| 50.88 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 51.66 | [Harvie Partridge](https://www.worldcubeassociation.org/persons/2015PART04) |
| 52.80 | [Thomas Patterson](https://www.worldcubeassociation.org/persons/2014PATT02) |
| 54.11 | [Daniel Chiu](https://www.worldcubeassociation.org/persons/2022CHIU06) |
| 54.71 | [Jaidon Adams](https://www.worldcubeassociation.org/persons/2018ADAM11) |
| 54.83 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 55.73 | [Christopher Kilgallon](https://www.worldcubeassociation.org/persons/2022KILG02) |
| 55.74 | [Edmund Finch](https://www.worldcubeassociation.org/persons/2023FINC02) |
| 56.32 | [Robert Yau](https://www.worldcubeassociation.org/persons/2009YAUR01) |
| 56.72 | [James Alonso](https://www.worldcubeassociation.org/persons/2018ALON07) |
| 57.80 | [Raphael Niman](https://www.worldcubeassociation.org/persons/2016NIMA01) |
| 58.12 | [Oliver Hutchings](https://www.worldcubeassociation.org/persons/2023HUTC01) |
| 58.13 | [Adam Black](https://www.worldcubeassociation.org/persons/2022BLAC01) |
| 58.18 | [Callum Hales-Jepp](https://www.worldcubeassociation.org/persons/2012HALE01) |
| 58.55 | [Rory Menary](https://www.worldcubeassociation.org/persons/2022MENA01) |
| 58.68 | [Chris Wall](https://www.worldcubeassociation.org/persons/2011WALL02) |
| 59.12 | [Tan Jun (陈俊)](https://www.worldcubeassociation.org/persons/2018JUNT01) |
| 59.30 | [Max Kwok U Sam (郭愉琛)](https://www.worldcubeassociation.org/persons/2018SAMK01) |
| 1:01.02 | [Dan Turner](https://www.worldcubeassociation.org/persons/2022TURN10) |
| 1:01.19 | [Ali Antar](https://www.worldcubeassociation.org/persons/2019ANTA02) |
| 1:02.11 | [Kris Lim](https://www.worldcubeassociation.org/persons/2022LIMK01) |
| 1:02.72 | [Adam Devere](https://www.worldcubeassociation.org/persons/2018DEVE02) |
| 1:02.77 | [Rufus Cripps](https://www.worldcubeassociation.org/persons/2022CRIP01) |
| 1:03.18 | [James Kyoichi Curry (ジェイムス 恭一)](https://www.worldcubeassociation.org/persons/2023CURR06) |
| 1:03.31 | [Murad Asgarov](https://www.worldcubeassociation.org/persons/2022ASGA01) |
| 1:03.47 | [Reuben Mould](https://www.worldcubeassociation.org/persons/2023MOUL02) |
| 1:03.71 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 1:03.89 | [Callum James Goodyear-Jørgensen](https://www.worldcubeassociation.org/persons/2012GOOD02) |
| 1:03.91 | [Charlie Harrison](https://www.worldcubeassociation.org/persons/2017HARR08) |
| 1:04.26 | [Monty Fox](https://www.worldcubeassociation.org/persons/2023FOXM01) |
| 1:04.36 | [Steven Cameron](https://www.worldcubeassociation.org/persons/2024CAME04) |
| 1:04.92 | [Jason Harley](https://www.worldcubeassociation.org/persons/2016HARL01) |

### Pyraminx

| Moving average | Person |
| ---: | :--- |
| 2.24 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 2.63 | [Edward Burgess](https://www.worldcubeassociation.org/persons/2018BURG03) |
| 2.69 | [Bo Forsell](https://www.worldcubeassociation.org/persons/2022FORS06) |
| 2.76 | [Zhiyuan Li (李致远)](https://www.worldcubeassociation.org/persons/2019LIZH08) |
| 2.79 | [Oliver Hutchings](https://www.worldcubeassociation.org/persons/2023HUTC01) |
| 2.96 | [Caleb Wolf Dunn](https://www.worldcubeassociation.org/persons/2022DUNN03) |
| 2.99 | [Nathan Olano](https://www.worldcubeassociation.org/persons/2018OLAN01) |
| 3.01 | [Jason Harley](https://www.worldcubeassociation.org/persons/2016HARL01) |
| 3.20 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 3.36 | [Rufus Cripps](https://www.worldcubeassociation.org/persons/2022CRIP01) |
| 3.48 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 3.50 | [Joel Keenan](https://www.worldcubeassociation.org/persons/2018KEEN02) |
| 3.53 | [Dan Turner](https://www.worldcubeassociation.org/persons/2022TURN10) |
| 3.57 | [Harry Allen](https://www.worldcubeassociation.org/persons/2023ALLE01) |
| 3.66 | [Raphael Niman](https://www.worldcubeassociation.org/persons/2016NIMA01) |
| 3.68 | [Satya Bhavesh Gala](https://www.worldcubeassociation.org/persons/2022GALA03) |
| 3.73 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 3.75 | [Blue James](https://www.worldcubeassociation.org/persons/2022JAME01) |
| 3.81 | [James Kyoichi Curry (ジェイムス 恭一)](https://www.worldcubeassociation.org/persons/2023CURR06) |
| 3.83 | [Ryan Chan](https://www.worldcubeassociation.org/persons/2023CHAN16) |
| 3.96 | [Tan Jun (陈俊)](https://www.worldcubeassociation.org/persons/2018JUNT01) |
| 4.02 | [Kai Cui](https://www.worldcubeassociation.org/persons/2019CUIK03) |
| 4.11 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 4.11 | [Kai Roff](https://www.worldcubeassociation.org/persons/2018ROFF01) |
| 4.12 | [Jaye Sloan](https://www.worldcubeassociation.org/persons/2022SLOA01) |
| 4.14 | [Noah Calderon-Kamata](https://www.worldcubeassociation.org/persons/2022CALD07) |
| 4.15 | [Matthew Ayre](https://www.worldcubeassociation.org/persons/2018AYRE02) |
| 4.15 | [Joseph Archibald](https://www.worldcubeassociation.org/persons/2019ARCH01) |
| 4.16 | [Alex Hamilton](https://www.worldcubeassociation.org/persons/2024HAMI07) |
| 4.20 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 4.38 | [Jake Brown](https://www.worldcubeassociation.org/persons/2020BROW01) |
| 4.42 | [Adam Black](https://www.worldcubeassociation.org/persons/2022BLAC01) |
| 4.43 | [Isaac Corker](https://www.worldcubeassociation.org/persons/2024CORK01) |
| 4.52 | [Zixuan Wang](https://www.worldcubeassociation.org/persons/2022WANG18) |
| 4.54 | [Luke Hubbard](https://www.worldcubeassociation.org/persons/2011HUBB01) |
| 4.56 | [Dominic Lumsden](https://www.worldcubeassociation.org/persons/2016LUMS01) |
| 4.57 | [Cameron Jones](https://www.worldcubeassociation.org/persons/2017JONE14) |
| 4.57 | [Anqi Yu](https://www.worldcubeassociation.org/persons/2018YUAN02) |
| 4.60 | [Liam Stuart Ferreira](https://www.worldcubeassociation.org/persons/2022FERR14) |
| 4.61 | [Max Kwok U Sam (郭愉琛)](https://www.worldcubeassociation.org/persons/2018SAMK01) |
| 4.63 | [Eli Jay](https://www.worldcubeassociation.org/persons/2014JAYE01) |
| 4.69 | [Thomas Mosedale](https://www.worldcubeassociation.org/persons/2022MOSE04) |
| 4.75 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 4.76 | [Max Tully](https://www.worldcubeassociation.org/persons/2023TULL04) |
| 4.79 | [James Robertson](https://www.worldcubeassociation.org/persons/2023ROBE05) |
| 4.82 | [James Alonso](https://www.worldcubeassociation.org/persons/2018ALON07) |
| 4.91 | [Marcus Siu](https://www.worldcubeassociation.org/persons/2016SIUM01) |
| 5.02 | [Jess Nock](https://www.worldcubeassociation.org/persons/2022NOCK01) |
| 5.05 | [Oliver Crook](https://www.worldcubeassociation.org/persons/2022CROO02) |
| 5.11 | [George Austin](https://www.worldcubeassociation.org/persons/2016AUST05) |

### Rubik's Clock

| Moving average | Person |
| ---: | :--- |
| 4.06 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 4.22 | [Caleb Wolf Dunn](https://www.worldcubeassociation.org/persons/2022DUNN03) |
| 4.51 | [Luke Burns](https://www.worldcubeassociation.org/persons/2020BURN06) |
| 4.57 | [Fengyuan Kelvin Lou (楼丰源)](https://www.worldcubeassociation.org/persons/2023LOUF01) |
| 4.81 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 5.13 | [Dorian Chan](https://www.worldcubeassociation.org/persons/2023DORI01) |
| 5.37 | [Matthew Stephenson](https://www.worldcubeassociation.org/persons/2022STEP04) |
| 5.40 | [Aidan Grainger](https://www.worldcubeassociation.org/persons/2018GRAI01) |
| 5.42 | [Monty Fox](https://www.worldcubeassociation.org/persons/2023FOXM01) |
| 5.52 | [Sam Shaw](https://www.worldcubeassociation.org/persons/2016SHAW02) |
| 5.67 | [Oliver Castledine](https://www.worldcubeassociation.org/persons/2018CAST08) |
| 5.71 | [Nicky Sim](https://www.worldcubeassociation.org/persons/2022SIMN02) |
| 5.72 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 5.81 | [Kris Lim](https://www.worldcubeassociation.org/persons/2022LIMK01) |
| 6.10 | [Rufus Cripps](https://www.worldcubeassociation.org/persons/2022CRIP01) |
| 6.15 | [Sam Jones](https://www.worldcubeassociation.org/persons/2023JONE09) |
| 6.24 | [Sophie Gilbert](https://www.worldcubeassociation.org/persons/2022GILB05) |
| 6.27 | [Adam Stringer](https://www.worldcubeassociation.org/persons/2023STRI02) |
| 6.32 | [Jimi Naysmith](https://www.worldcubeassociation.org/persons/2022NAYS02) |
| 6.35 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 6.49 | [Tan Jun (陈俊)](https://www.worldcubeassociation.org/persons/2018JUNT01) |
| 6.64 | [Thomas Bevan](https://www.worldcubeassociation.org/persons/2017BEVA01) |
| 6.65 | [Cameron Littlejohn](https://www.worldcubeassociation.org/persons/2022LITT01) |
| 6.85 | [Ed Scholey](https://www.worldcubeassociation.org/persons/2020SCHO03) |
| 6.88 | [Adam Devere](https://www.worldcubeassociation.org/persons/2018DEVE02) |
| 7.03 | [Oscar Coleman Green](https://www.worldcubeassociation.org/persons/2018GREE09) |
| 7.06 | [Matt Prestwich](https://www.worldcubeassociation.org/persons/2016PRES04) |
| 7.12 | [Isaac Corker](https://www.worldcubeassociation.org/persons/2024CORK01) |
| 7.13 | [Ryan Eckersley](https://www.worldcubeassociation.org/persons/2019ECKE02) |
| 7.15 | [Hayden Wallace](https://www.worldcubeassociation.org/persons/2023WALL05) |
| 7.17 | [James Kyoichi Curry (ジェイムス 恭一)](https://www.worldcubeassociation.org/persons/2023CURR06) |
| 7.25 | [Harry Allen](https://www.worldcubeassociation.org/persons/2023ALLE01) |
| 7.25 | [Dan Turner](https://www.worldcubeassociation.org/persons/2022TURN10) |
| 7.31 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 7.33 | [Ryan Jones](https://www.worldcubeassociation.org/persons/2012JONE03) |
| 7.33 | [Tom Damsell-Walker](https://www.worldcubeassociation.org/persons/2019DAMS01) |
| 7.35 | [Murad Asgarov](https://www.worldcubeassociation.org/persons/2022ASGA01) |
| 7.45 | [Matas Pabreza](https://www.worldcubeassociation.org/persons/2023PABR01) |
| 7.45 | [Isaac Campbell](https://www.worldcubeassociation.org/persons/2023CAMP24) |
| 7.46 | [Max Kwok U Sam (郭愉琛)](https://www.worldcubeassociation.org/persons/2018SAMK01) |
| 7.53 | [Theo Proferes](https://www.worldcubeassociation.org/persons/2019PROF01) |
| 7.57 | [Ezra Hirschi](https://www.worldcubeassociation.org/persons/2019HIRS01) |
| 7.59 | [Sam Spendla](https://www.worldcubeassociation.org/persons/2015SPEN01) |
| 7.69 | [Patrick Drew Dwyer](https://www.worldcubeassociation.org/persons/2019DWYE01) |
| 7.69 | [Jasmine Eastwood](https://www.worldcubeassociation.org/persons/2022EAST01) |
| 7.84 | [George Railton](https://www.worldcubeassociation.org/persons/2022RAIL01) |
| 7.85 | [Satya Bhavesh Gala](https://www.worldcubeassociation.org/persons/2022GALA03) |
| 7.89 | [Dominic Seaton](https://www.worldcubeassociation.org/persons/2022SEAT02) |
| 7.91 | [Callum Saunders Hibbert](https://www.worldcubeassociation.org/persons/2023HIBB01) |
| 8.01 | [Reuben Ingram](https://www.worldcubeassociation.org/persons/2023INGR05) |

### Skewb

| Moving average | Person |
| ---: | :--- |
| 2.81 | [Ariel Benchetrit](https://www.worldcubeassociation.org/persons/2019BENC04) |
| 3.62 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 3.74 | [George Scholey](https://www.worldcubeassociation.org/persons/2015SCHO05) |
| 3.82 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 3.84 | [Harry Owen](https://www.worldcubeassociation.org/persons/2017OWEN01) |
| 3.96 | [Matthew Stephenson](https://www.worldcubeassociation.org/persons/2022STEP04) |
| 4.02 | [Karam Al-Robaie](https://www.worldcubeassociation.org/persons/2016ALRO01) |
| 4.07 | [Daniel Tidsey](https://www.worldcubeassociation.org/persons/2016TIDS01) |
| 4.19 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 4.23 | [Harvie Partridge](https://www.worldcubeassociation.org/persons/2015PART04) |
| 4.28 | [Fabian Houston](https://www.worldcubeassociation.org/persons/2023HOUS04) |
| 4.31 | [Tom Nugent](https://www.worldcubeassociation.org/persons/2022NUGE01) |
| 4.38 | [Tom Wilkinson](https://www.worldcubeassociation.org/persons/2019WILK04) |
| 4.39 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 4.47 | [Pierre Ming L. Debroe](https://www.worldcubeassociation.org/persons/2022DEBR02) |
| 4.59 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 4.66 | [Sam Jones](https://www.worldcubeassociation.org/persons/2023JONE09) |
| 4.69 | [Ruben McEwan](https://www.worldcubeassociation.org/persons/2022MCEW01) |
| 4.75 | [Caleb Wolf Dunn](https://www.worldcubeassociation.org/persons/2022DUNN03) |
| 4.76 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 4.76 | [Jaye Sloan](https://www.worldcubeassociation.org/persons/2022SLOA01) |
| 4.78 | [Keya Shah](https://www.worldcubeassociation.org/persons/2022SHAH05) |
| 4.81 | [Naglis Peciulis](https://www.worldcubeassociation.org/persons/2017PECI01) |
| 4.84 | [Archie Fedulov](https://www.worldcubeassociation.org/persons/2022FEDU01) |
| 4.88 | [Eli Jay](https://www.worldcubeassociation.org/persons/2014JAYE01) |
| 5.11 | [Isaac Corker](https://www.worldcubeassociation.org/persons/2024CORK01) |
| 5.15 | [Daniel Hamilton](https://www.worldcubeassociation.org/persons/2023HAMI12) |
| 5.16 | [Charlie Harrison](https://www.worldcubeassociation.org/persons/2017HARR08) |
| 5.20 | [Ryan Chan](https://www.worldcubeassociation.org/persons/2023CHAN16) |
| 5.24 | [Harry Allen](https://www.worldcubeassociation.org/persons/2023ALLE01) |
| 5.26 | [Billie Hammill](https://www.worldcubeassociation.org/persons/2015HAMM01) |
| 5.26 | [Cameron Jones](https://www.worldcubeassociation.org/persons/2017JONE14) |
| 5.38 | [Marcus Siu](https://www.worldcubeassociation.org/persons/2016SIUM01) |
| 5.41 | [Aidan Grainger](https://www.worldcubeassociation.org/persons/2018GRAI01) |
| 5.41 | [Adejuwon Adebusuyi Oluwemimo](https://www.worldcubeassociation.org/persons/2022OLUW01) |
| 5.44 | [Rufus Prabhu-Desai](https://www.worldcubeassociation.org/persons/2023PRAB09) |
| 5.46 | [Ryan Eckersley](https://www.worldcubeassociation.org/persons/2019ECKE02) |
| 5.47 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 5.58 | [Katie Moughan](https://www.worldcubeassociation.org/persons/2017DAVI03) |
| 5.58 | [Fengyuan Kelvin Lou (楼丰源)](https://www.worldcubeassociation.org/persons/2023LOUF01) |
| 5.59 | [James Tuppenney](https://www.worldcubeassociation.org/persons/2018TUPP02) |
| 5.62 | [Sean Moran](https://www.worldcubeassociation.org/persons/2016MORA24) |
| 5.63 | [Anqi Yu](https://www.worldcubeassociation.org/persons/2018YUAN02) |
| 5.71 | [Fabio Rossi](https://www.worldcubeassociation.org/persons/2022ROSS02) |
| 5.72 | [Ollie Turner](https://www.worldcubeassociation.org/persons/2022TURN11) |
| 5.72 | [Dorian Chan](https://www.worldcubeassociation.org/persons/2023DORI01) |
| 5.73 | [Benjamin Grzesiak](https://www.worldcubeassociation.org/persons/2018GRZE01) |
| 5.78 | [Dan Turner](https://www.worldcubeassociation.org/persons/2022TURN10) |
| 5.78 | [Callum Saunders Hibbert](https://www.worldcubeassociation.org/persons/2023HIBB01) |
| 5.80 | [William Casey](https://www.worldcubeassociation.org/persons/2023CASE08) |

### Square-1

| Moving average | Person |
| ---: | :--- |
| 8.15 | [Isaac Corker](https://www.worldcubeassociation.org/persons/2024CORK01) |
| 8.73 | [Charlie Stark](https://www.worldcubeassociation.org/persons/2014STAR05) |
| 8.79 | [Fengyuan Kelvin Lou (楼丰源)](https://www.worldcubeassociation.org/persons/2023LOUF01) |
| 9.58 | [Daniel Partridge](https://www.worldcubeassociation.org/persons/2022PART02) |
| 9.61 | [Ryan Eckersley](https://www.worldcubeassociation.org/persons/2019ECKE02) |
| 9.69 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 9.92 | [Dorian Chan](https://www.worldcubeassociation.org/persons/2023DORI01) |
| 10.57 | [Austin Ritchie](https://www.worldcubeassociation.org/persons/2022RITC01) |
| 10.82 | [Marcus Siu](https://www.worldcubeassociation.org/persons/2016SIUM01) |
| 10.82 | [Danny Morgan](https://www.worldcubeassociation.org/persons/2019MORG10) |
| 11.10 | [Caleb Wolf Dunn](https://www.worldcubeassociation.org/persons/2022DUNN03) |
| 11.16 | [Aidan Grainger](https://www.worldcubeassociation.org/persons/2018GRAI01) |
| 11.23 | [Luke Burns](https://www.worldcubeassociation.org/persons/2020BURN06) |
| 11.69 | [Billie Hammill](https://www.worldcubeassociation.org/persons/2015HAMM01) |
| 11.84 | [George Railton](https://www.worldcubeassociation.org/persons/2022RAIL01) |
| 11.92 | [Naglis Peciulis](https://www.worldcubeassociation.org/persons/2017PECI01) |
| 12.16 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 12.26 | [Ben Stokes](https://www.worldcubeassociation.org/persons/2018STOK01) |
| 12.56 | [Simon Crawford](https://www.worldcubeassociation.org/persons/2008CRAW01) |
| 12.72 | [Ryan Chan](https://www.worldcubeassociation.org/persons/2023CHAN16) |
| 13.01 | [George Scholey](https://www.worldcubeassociation.org/persons/2015SCHO05) |
| 13.09 | [Daniel Tidsey](https://www.worldcubeassociation.org/persons/2016TIDS01) |
| 13.22 | [Karam Al-Robaie](https://www.worldcubeassociation.org/persons/2016ALRO01) |
| 13.32 | [Anqi Yu](https://www.worldcubeassociation.org/persons/2018YUAN02) |
| 13.35 | [Ainesh Sevellaraja](https://www.worldcubeassociation.org/persons/2012SEVE01) |
| 13.45 | [Sean Moran](https://www.worldcubeassociation.org/persons/2016MORA24) |
| 13.55 | [Matthew Stephenson](https://www.worldcubeassociation.org/persons/2022STEP04) |
| 13.67 | [Charlie Harrison](https://www.worldcubeassociation.org/persons/2017HARR08) |
| 14.04 | [Oliver Castledine](https://www.worldcubeassociation.org/persons/2018CAST08) |
| 14.05 | [Eleanor Sinnott](https://www.worldcubeassociation.org/persons/2016SINN01) |
| 14.20 | [Kaisei Brittain](https://www.worldcubeassociation.org/persons/2022BRIT04) |
| 14.49 | [Dominic Lumsden](https://www.worldcubeassociation.org/persons/2016LUMS01) |
| 14.61 | [Benjamin Grzesiak](https://www.worldcubeassociation.org/persons/2018GRZE01) |
| 15.15 | [Jacob Chambers](https://www.worldcubeassociation.org/persons/2017CHAM09) |
| 15.39 | [Tan Jun (陈俊)](https://www.worldcubeassociation.org/persons/2018JUNT01) |
| 15.40 | [Sam Williams](https://www.worldcubeassociation.org/persons/2023WILL30) |
| 15.46 | [Henry Martin](https://www.worldcubeassociation.org/persons/2024MART15) |
| 15.47 | [Dan Turner](https://www.worldcubeassociation.org/persons/2022TURN10) |
| 15.90 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 15.93 | [Satya Bhavesh Gala](https://www.worldcubeassociation.org/persons/2022GALA03) |
| 15.95 | [Harvie Partridge](https://www.worldcubeassociation.org/persons/2015PART04) |
| 15.97 | [Joe Greenland](https://www.worldcubeassociation.org/persons/2019GREE02) |
| 15.98 | [Stephen Waller](https://www.worldcubeassociation.org/persons/2017WALL12) |
| 16.18 | [Ryan Tang](https://www.worldcubeassociation.org/persons/2022TANG05) |
| 16.27 | [Christopher Kilgallon](https://www.worldcubeassociation.org/persons/2022KILG02) |
| 16.39 | [Callum Saunders Hibbert](https://www.worldcubeassociation.org/persons/2023HIBB01) |
| 16.52 | [Jason Harley](https://www.worldcubeassociation.org/persons/2016HARL01) |
| 16.77 | [Finley Norris](https://www.worldcubeassociation.org/persons/2022NORR01) |
| 16.77 | [Alexander Edelman](https://www.worldcubeassociation.org/persons/2020EDEL01) |
| 16.77 | [Yan-Heng Zhang](https://www.worldcubeassociation.org/persons/2022ZHAN40) |

### 3x3x3 With Feet

| Moving average | Person |
| ---: | :--- |
| 34.85 | [Ben Ridley](https://www.worldcubeassociation.org/persons/2016RIDL01) |
| 38.76 | [Adam Swaine](https://www.worldcubeassociation.org/persons/2017SWAI01) |
| 41.57 | [Callum Hales-Jepp](https://www.worldcubeassociation.org/persons/2012HALE01) |
| 46.87 | [Harry Savage](https://www.worldcubeassociation.org/persons/2013SAVA01) |
| 47.88 | [Charlie Stark](https://www.worldcubeassociation.org/persons/2014STAR05) |
| 1:07.87 | [Chris Mills](https://www.worldcubeassociation.org/persons/2014MILL04) |
| 1:07.97 | [Daniel Sheppard](https://www.worldcubeassociation.org/persons/2009SHEP01) |
| 1:09.68 | [Jialin Zhou](https://www.worldcubeassociation.org/persons/2013ZHOU19) |
| 1:11.01 | [Billie Hammill](https://www.worldcubeassociation.org/persons/2015HAMM01) |
| 1:15.36 | [Fabio Schwandt](https://www.worldcubeassociation.org/persons/2014SCHW02) |
| 1:16.26 | [Ben Coppin](https://www.worldcubeassociation.org/persons/2013COPP01) |
| 1:18.01 | [Robert Yau](https://www.worldcubeassociation.org/persons/2009YAUR01) |
| 1:22.02 | [Ainesh Sevellaraja](https://www.worldcubeassociation.org/persons/2012SEVE01) |
| 1:27.74 | [Alexander Lau](https://www.worldcubeassociation.org/persons/2011LAUA01) |
| 1:36.64 | [Daniel Ramsden](https://www.worldcubeassociation.org/persons/2017RAMS02) |
| 1:42.74 | [Bertie Longden](https://www.worldcubeassociation.org/persons/2014LONG06) |
| 1:43.04 | [Callum James Goodyear-Jørgensen](https://www.worldcubeassociation.org/persons/2012GOOD02) |
| 1:46.38 | [Chris Wall](https://www.worldcubeassociation.org/persons/2011WALL02) |
| 2:02.69 | [James Molloy](https://www.worldcubeassociation.org/persons/2011MOLL01) |

### Rubik's Magic

| Moving average | Person |
| ---: | :--- |
| 1.90 | [Andrew Coghill](https://www.worldcubeassociation.org/persons/2009COGH01) |
| 2.05 | [Jason Gyani](https://www.worldcubeassociation.org/persons/2008GYAN01) |
| 2.23 | [Tristan Penson](https://www.worldcubeassociation.org/persons/2009PENS02) |
| 2.27 | [Breandan Vallance](https://www.worldcubeassociation.org/persons/2007VALL01) |
| 2.38 | [Ben Whitmore](https://www.worldcubeassociation.org/persons/2009WHIT01) |
| 2.45 | [James Dean Ludlow](https://www.worldcubeassociation.org/persons/2009LUDL02) |
| 2.47 | [Sean Connolly](https://www.worldcubeassociation.org/persons/2004CONN01) |
| 2.47 | [Charlie Cooper](https://www.worldcubeassociation.org/persons/2007COOP01) |
| 2.47 | [Leon Parfitt](https://www.worldcubeassociation.org/persons/2010PARF01) |
| 2.48 | [Robert Yau](https://www.worldcubeassociation.org/persons/2009YAUR01) |
| 2.55 | [Elliot Penson](https://www.worldcubeassociation.org/persons/2009PENS01) |
| 2.59 | [Adam Wills](https://www.worldcubeassociation.org/persons/2008WILL03) |
| 2.62 | [Chris Wall](https://www.worldcubeassociation.org/persons/2011WALL02) |
| 2.68 | [Greg Austin](https://www.worldcubeassociation.org/persons/2006AUST01) |
| 2.73 | [Jude Wright](https://www.worldcubeassociation.org/persons/2008WRIG02) |
| 2.73 | [Andrea Javier](https://www.worldcubeassociation.org/persons/2010JAVI01) |
| 2.83 | [James Molloy](https://www.worldcubeassociation.org/persons/2011MOLL01) |
| 2.87 | [Michael Erskine](https://www.worldcubeassociation.org/persons/2008ERSK01) |
| 2.91 | [Daniel Sheppard](https://www.worldcubeassociation.org/persons/2009SHEP01) |
| 3.76 | [Dan Harris](https://www.worldcubeassociation.org/persons/2003HARR01) |
| 4.20 | [Joey Gouly](https://www.worldcubeassociation.org/persons/2007GOUL01) |

### Master Magic

| Moving average | Person |
| ---: | :--- |
| 3.61 | [Thom Barlow](https://www.worldcubeassociation.org/persons/2006BARL01) |
| 3.67 | [James Dean Ludlow](https://www.worldcubeassociation.org/persons/2009LUDL02) |
| 4.08 | [Daniel Sheppard](https://www.worldcubeassociation.org/persons/2009SHEP01) |
| 4.16 | [Jason Gyani](https://www.worldcubeassociation.org/persons/2008GYAN01) |
| 4.17 | [James Molloy](https://www.worldcubeassociation.org/persons/2011MOLL01) |
| 4.51 | [Chris Wall](https://www.worldcubeassociation.org/persons/2011WALL02) |
| 5.18 | [Charlie Cooper](https://www.worldcubeassociation.org/persons/2007COOP01) |
| 5.23 | [Robert Yau](https://www.worldcubeassociation.org/persons/2009YAUR01) |
| 5.40 | [Andrew Coghill](https://www.worldcubeassociation.org/persons/2009COGH01) |
| 5.47 | [Sean Connolly](https://www.worldcubeassociation.org/persons/2004CONN01) |
| 7.58 | [Michael Erskine](https://www.worldcubeassociation.org/persons/2008ERSK01) |
| 7.90 | [Adam Wills](https://www.worldcubeassociation.org/persons/2008WILL03) |
| 9.32 | [Joey Gouly](https://www.worldcubeassociation.org/persons/2007GOUL01) |


<a href="https://github.com/simonkellly/wca_statistics_uk" class="github-corner" aria-label="View source on Github"><svg width="80" height="80" viewBox="0 0 250 250" style="fill:#151513; color:#fff; position: absolute; top: 0; border: 0; right: 0;" aria-hidden="true"><path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path><path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2" fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path><path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z" fill="currentColor" class="octo-body"></path></svg></a><style>.github-corner:hover .octo-arm{animation:octocat-wave 560ms ease-in-out}@keyframes octocat-wave{0%,100%{transform:rotate(0)}20%,60%{transform:rotate(-25deg)}40%,80%{transform:rotate(10deg)}}@media (max-width:500px){.github-corner:hover .octo-arm{animation:none}.github-corner .octo-arm{animation:octocat-wave 560ms ease-in-out}}</style>
