<div align="center">
  
# Green Algorithms 

**www.green-algorithms.org**

---

<img src="assets/images/screenshot_app.png" width="500">

</div>

## Methods and data

The methodology behind the Green Algorithms project is described in our pre-print:
_Coming soon_

All the data used for the calculator are in the `/data` directory above. 

## Questions, issues, suggestions? Want to contribute?

Start by opening an issue here, and we will try to address it quickly:
https://github.com/GreenAlgorithms/green-algorithms-tool/issues

You can also contact us at: green.algorithms@gmail.com

## How to cite this work
> L. Lannelongue\*, J. Grealey\* and M. Inouye, 
“Green Algorithms: A simple method and tool for quantifying the carbon emissions of computation” (in preparation), 
www.green-algorithms.org (2020)

_\* Contributed equally to this work_

## FAQ

> Should I include the number of processors, number of cores, or number of threads used?

For CPUs, the number of cores (CPUs usually have 4-12 cores per processor). For GPUs, the number of GPUs. If using multi-threading on CPUs (i.e. using more threads than cores), still input the number of cores, but be aware that yourr emissions might be underestimated. 

> What if my processor is not in the list? 

You can find the TDP (Thermal Design Power) value on the manufacturer's website, and email us so we can add it for next time! 

> What if my country is not in the list? 

Email us so we can add it to the list (some countries are more secretive than others about their energy mix). You can use the world average, or a close proxy, for your estimations.

> Can I compare algorithms impact independantly of the location?

Yes, simply use the "Energy needed" (in W) displayed next to the carbon emissions. 

> How do I find the usage factor of my processors?

It depends on your system. If you're using SLURM for example, you can find this information with the command ... 

> How do I estimate my PSF (Pragmatic Scaling Factor)?

Try to estimate how many times you need to run your full analysis to get results you're happy with. It can be trials and errors, parameters optimisations, memory issues etc. 

> What if I found a bug in the tool?

[Open an issue](https://github.com/GreenAlgorithms/green-algorithms-tool/issues) on the GitHub so that we can look at it. 

## Credits 

- the app was designed using [Plotly Dash](https://plot.ly/dash/)
- The background image is realised by [Ed Hawkins](https://showyourstripes.info) from the University of Reading
- The icons used are under [CC Attribution licence](https://creativecommons.org/licenses/by/4.0/) 
and have been designed by 
[Laura Reen](https://icon-icons.com/icon/weather-co2-pollution/90772),
[Jeremiah](https://icon-icons.com/icon/preferences-system-power-energy/103835),
[Sergei Kokota](https://icon-icons.com/icon/tree-greenery-nature/53329),
[Baianat](https://icon-icons.com/icon/car/61086) and
[RoundIcons](https://icon-icons.com/icon/plane-airplane/89770)

## Licence

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-shield]][cc-by]

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
