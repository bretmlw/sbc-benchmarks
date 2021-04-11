# sbc-benchmarks
A list of benchmark results for various Single Board Computers (SBC) which are used in my blog posts at https://bret.dk

I understand that these aren't entirely indicative of true performance due to the differences in operating systems, kernels, compilers etc etc however a lot of people still use these as a rough estimate of performance so I'm compiling everything I can test here.

If you have a specific test or benchmark you'd like me to run and provide results for on any of these boards then please raise an issue or contact me via <a href="https://twitter.com/bretweber">Twitter</a> or by leaving a comment on the relevant board's review on my <a href="https://bret.dk">website</a>.

(In cases where I've benched an overclocked board, I've added `-overclock-XXXX` to the end of the results file and included full overclocking options at the top of that results file)

All iperf3 results are tested with default settings to a server on a local network confirmed to be able to push 1Gbit. On devices where both ethernet and WiFi are available, separate results (iperf & iperf-wifi) will be tested. All WiFi tests are done from a distance of 1m with line of sight to the router.

When it comes to temperatures in any benchmark results, all boards are tested at stock with no heatsinks attached in a room set to 25 degrees celsius. Though Raspberry Pi 4 Model B tests at the moment are a little skewed as I do have a case/heatsink on that so WiFi iperf3 tests and the temperatures will be different to a stock Pi 4. I'll get round to taking it off for testing at some point.
