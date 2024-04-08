![Captura de tela 2024-04-07 164109](https://github.com/Homerlucas/Presidents-Heights/assets/113539596/34f94be2-2976-4dd2-bef2-cc6f291616f1)
First, we'll call the libraries we'll be using in this project

![Captura de tela 2024-04-07 164114](https://github.com/Homerlucas/Presidents-Heights/assets/113539596/a43af90e-1b1e-4c7f-a5f8-bbd88cfb3599)
We’ll use the Pandas package to read the file and extract this information

![Captura de tela 2024-04-07 164120](https://github.com/Homerlucas/Presidents-Heights/assets/113539596/91aeb237-0091-49f1-8136-45013d32d2be)
Now that we have this data array, we can compute a variety of summary statistics:

![Captura de tela 2024-04-07 164126](https://github.com/Homerlucas/Presidents-Heights/assets/113539596/7bc4b658-58ac-42af-b7b0-7c711522b462)
Note that in each case, the aggregation operation reduced the entire array to a single summarizing value, which gives us information about the distribution of values. We may also wish to compute quantiles:

![Captura de tela 2024-04-07 164130](https://github.com/Homerlucas/Presidents-Heights/assets/113539596/ac240bc5-3d30-49e1-a231-3252e948f4b0)
We see that the median height of US presidents is 182 cm, or just shy of six feet. Of course, sometimes it’s more useful to see a visual representation of this data, which we can accomplish using tools in Matplotlib:

![Captura de tela 2024-04-07 164139](https://github.com/Homerlucas/Presidents-Heights/assets/113539596/5476fa34-d532-4bd1-96f3-428038706c52)
These aggregates are some of the fundamental pieces of exploratory data science that we’ll explore in more depth in later coming projects.
