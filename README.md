Lab 2-1 Creating a Reproducible Example (Reprex) in R
================

# Create a numeric vector

> numbers \<- c(5, 10, 15, 20, 25)
>
> # Calculate the sum of the vector
>
> total_sum \<- sum(number)

# Load the reprex library

> library(reprex)
>
> # The code wrapped in reprex
>
> reprex({ + \# Create a numeric vector + numbers \<- c(5, 10, 15, 20,
> 25) +  
> + \# Calculate the sum of the vector + total_sum \<- sum(numbers) +  
> + \# Print the result + print(total_sum) + })
