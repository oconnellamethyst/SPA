Here, I have a script that will run the simulation 10,000 times (should take less than an hour) and save each result to a folder, then declare the winner.
Is that operation expensive? Writing 10,000 files will occupy 10,000*2 blocks, or about 80MB, but it's worth it.
Run this program if you want to ensure all your students are happy.

To run 1,000 trials and pick the best in terms of number of top 3rd choices assigned, run bash do1000.sh (took 2 minutes on an old laptop)
To run 10,000 trials, run do1000.sh (should take about one half episode of the Simpsons ~16 minutes)
