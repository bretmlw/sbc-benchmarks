# sbc-benchmarks
A list of benchmark results for various Single Board Computers (SBC) which are used in my blog posts at https://bret.dk

## Disclaimer
I understand that these aren't entirely indicative of true performance due to the differences in operating systems, kernels, compilers etc etc however a lot of people still use these as a rough estimate of performance so I'm compiling everything I can test here. I'm not doing this for scientific research, it's more out of an interest for random hardware and curiosity. I'll try to keep everything as fair and similar as possible but don't come after me if something's a bit off 🤞

## Testing Environment
All boards are tested in a room at 25 degrees celsius with no heatsinks/active cooling. Ethernet tests are performed via the same CAT6 cable directly into the router (ComHem C2 WiFi, it's a bit crap but it works for this) and WiFi tests are performed at a distance of 1m with direct line of sight to the router. All benchmarks are performed using a SanDisk Extreme Pro 64GB A2 grade microSD card to try and remove any bottlenecks/issues.

## iperf3
All iperf3 results are tested with default settings to a Debian 10 server on a local network confirmed to be able to push 1Gbit. On devices where both ethernet and WiFi are available, separate results (iperf & iperf-wifi) will be provided.

## What are the 'overclock-XXXX' results about?
Where temperature headroom allows, I'll test boards whilst overclocked as potential buyers may be interested in these stats too. Any results obtained from an overclocked board will have `-overclock-XXXX` added to the end of the results filename, with full overclocking options/settings used at the top of that results file.

## Raspberry Pi 4 Model B 2GB Note
At the moment the Raspberry Pi 4 Model B tests are a little skewed as I do have a full metal case/heatsink/fans etc on that so WiFi tests and the temperatures will be different to a stock Pi 4. I'll get round to taking it off for testing at some point and will update results when this happens.

## Want to see something in particular?
If you have a specific test or benchmark you'd like me to run and provide results for on any of these boards then please raise an issue or contact me via <a href="https://twitter.com/bretweber">Twitter</a> or by leaving a comment on the relevant board's review on my <a href="https://bret.dk">website</a>.
