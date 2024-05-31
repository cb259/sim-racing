# Assetto Corsa Competizion (ACC) Car Setups
These are car setups that I have created. The table below details the setups, which cars and tracks they have been tested with as well as my notes.

## ACC Setup References
These resources have helped me understand setup values and create better setups.
- [HOW TO FIX OVERSTEER AND UNDERSTEER IN ACC](https://coachdaveacademy.com/tutorials/how-to-fix-oversteer-and-understeer-in-acc/)
- [How to build your own car setup in ACC for every CAR using only 2 steps](https://www.youtube.com/watch?v=wqpRe7A9rag)
- [How to build your own car setup in ACC for every CAR in 2 Steps (part2)](https://www.youtube.com/watch?v=0zLV-Td2-tY)
- [How to build your own car setup in ACC for every CAR Part 3](https://www.youtube.com/watch?v=0qd8wmdywN4)
- [How to Build the Perfect Setup FOR YOU in ACC 1.10 - Meta Setup Guide - Assetto Corsa Competizione](https://www.youtube.com/watch?v=uir0aLcOzsk)
- [THE ULTIMATE ACC CAR SETUP GUIDE](https://coachdaveacademy.com/tutorials/the-ultimate-acc-car-setup-guide/)

## Experimentation Ideas
### Problem: Understeer
Details:
- Car understeers going into sharp corners.
- Car understeers going through long, sweeping corners.

Ideas:
- Decrease rear toe-in to make the car more neutral/oversteer. This is for turn-in or mid-corner understeer.
- Decrease the front slow bump setting to encourage the car to be more neutral.
- Increase rear slow bump settings to encourage the car to rotate coming out of the corners.
- Increase rear rebound to eradicate understeer and bring the car closer to an oversteer bias on braking.
- Decrease front spring rates. Prevents the front from becoming unloaded.
    - Detractor - The rear will become unloaded quicker, promoting oversteer.
- Increase rear spring rates.
    - Detractor - Can make the rear twitchy, especially on slow corners where mechanical grip is important.
- Increase front bump stop range and stiffen the rate.
- Lower differential preload.

## My Setup Details
Note: This section was a table I started when building my first setup. I would track each change as a different version. As I expanded to additional cars and tracks, this method was no longer scalable, therefore this section is no longer updated. Here are a few notes to steer you to what you may be looking for:
1. My setups are named Working_Vxx (Where xx starts at 01 and increments)
2. My setups can be different between cars. That means Working_V05 for one car is likely different than the same version on another car.
3. I learn as I go, so the most effective setup settings are likely the newest ones (Go by file date).
4. Setups not following the Working_Vxx naming convention are those that I have downloaded elsewhere. These are free setups provided by others. Contact me if one of your setups is listed and I will make sure you get appropriate credit.

<table>
  <tr>
    <th>Setup Name</th>
    <th>Starting Setup</th>
    <th>Changes made (Compared to starting setup)</th>
    <th>Cars Tested</th>
    <th>Tracks Tested</th>
    <th>Setup Notes</th>
  </tr>
  <tr>
    <td>Working_v0</td>
    <td>N/A</td>
    <td>N/A</td>
    <td>BMW M6 GT3</td>
    <td>SPA</td>
    <td>Starting setup</td>
  </tr>
  <tr>
    <td>Working_v1</td>
    <td>Working_v0</td>
    <td>Unknown</td>
    <td>BMW M6 GT3</td>
    <td>SPA</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>Working_v2</td>
    <td>Working_v1</td>
    <td>Increase rear ride height from 57mm to 61mm.</td>
    <td>BMW M6 GT3</td>
    <td>SPA</td>
    <td>Working to address understeer</td>
  </tr>
  <tr>
    <td>Working_v3</td>
    <td>Working_v2</td>
    <td>
        <ul>
            <li>Reduced steering ratio from 14 to 12.</li>
            <li>Increased front bumpstop range from 5 to 8.</li>
            <li>Reduced rear bumpstop range from 9-7</li>
        </ul>
    </td>
    <td>BMW M6 GT3</td>
    <td>SPA</td>
    <td></td>
  </tr>
  <tr>
    <td>Working_v4</td>
    <td>Working_v3</td>
    <td>
        <ul>
            <li>Reduced steering ratio from 12 to 10.</li>
        </ul>
    </td>
    <td>BMW M6 GT3</td>
    <td>SPA</td>
    <td></td>
  </tr>
  <tr>
    <td>Working_v5</td>
    <td>Working_v4</td>
    <td>
        <ul>
            <li>Reduced front tire pressure from 25.2 to 24.</li>
            <li>Increased rear tire pressure from 24.6 to 24.8.</li>
            <li>Reduced rear brake bias from 60.1 to 53.2</li>
        </ul>
    </td>
    <td>BMW M6 GT3</td>
    <td>SPA</td>
    <td>Too much understeer.</td>
  </tr>
  <tr>
    <td>Working_v6</td>
    <td>Working_v4</td>
    <td>
        <ul>
            <li>Reduced rear wing from 7 to 5.</li>
        </ul>
    </td>
    <td>BMW M6 GT3</td>
    <td>SPA</td>
    <td>Trying to reduce understeer in fast corners.</td>
  </tr>
  <tr>
    <td>Working_v7</td>
    <td>Working_v6</td>
    <td>
        <ul>
            <li>Increased rear anti-roll bar from 2 to 4.</li>
        </ul>
    </td>
    <td>BMW M6 GT3</td>
    <td>SPA</td>
    <td>Too much understeer.</td>
  </tr>
  <tr>
    <td>Working_v8</td>
    <td>Working_v7</td>
    <td>
        <ul>
            <li>Decreased front tyre pressure from 24.9 to 24.7.</li>
        </ul>
    </td>
    <td>BMW M6 GT3</td>
    <td>SPA</td>
    <td>Front tyres were running 27.0 hot at the previous value.</td>
  </tr>
  <tr>
    <td>Working_v9</td>
    <td>Working_v8</td>
    <td>
        <ul>
            <li>Decreased front tyre pressure from 24.7 to 24.3.</li>
        </ul>
    </td>
    <td>BMW M6 GT3</td>
    <td>SPA</td>
    <td>Front tyres were running 27.2 hot at the previous value.</td>
  </tr>
</table>