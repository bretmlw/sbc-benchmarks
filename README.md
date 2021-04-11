# sbc-benchmarks
A list of benchmark results for various Single Board Computers (SBC) which are used in my blog posts at https://bret.dk

I understand that these aren't entirely indicative of true performance due to the differences in operating systems, kernels, compilers etc etc however a lot of people still use these as a rough estimate of performance so I'm compiling everything I can test here.

If you have a specific test or benchmark you'd like me to run and provide results for on any of these boards then please raise an issue or contact me via <a href="https://twitter.com/bretweber">Twitter</a> or by leaving a comment on the relevant board's review on my <a href="https://bret.dk">website</a>.

(In cases where I've benched an overclocked board, I've added `-overclock-XXXX` to the end of the results file and included full overclocking options at the top of that results file)

All iperf3 results are tested with default settings to a server on a local network confirmed to be able to push 1Gbit. On devices where both ethernet and WiFi are available, separate results (iperf & iperf-wifi) will be tested.
