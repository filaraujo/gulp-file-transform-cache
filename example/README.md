
### Example

`node example.js`

1. Run the command above. The 1st time you run it, note the amount of time it takes to complete.
A forced delay has been added to simulate a transformation that performs an expensive operation.  

2. Run the command again. Note that the result comes back instantly. Because the prior run
cached the result of the transformation, the time cost of the transformation is avoided.

3. Update or touch one of the txt files in the data directory and run the command again. Note that
the transformation again takes some time to complete, as the cached version of the transformation
was not fresh.
