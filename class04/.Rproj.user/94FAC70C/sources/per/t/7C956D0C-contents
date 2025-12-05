# Question 1
source("http://thegrantlab.org/misc/cdc.R")
tail(cdc$weight, n = 20)

# Question 2
plot(cdc$height, cdc$weight,
     xlab = "Height (inchs)",
     ylab = "Weight (pounds)")

# Question 3
cor(cdc$height, cdc$weight)
cor.test(cdc$height, cdc$weight)

# Question 4
height_m <- cdc$height * 0.0254
weight_kg <- cdc$weight * 0.4535

# Question 5
bmi <- (weight_kg)/(height_m^2)
plot(cdc$height, bmi, ylab = "BMI")

# Question 6
cor(cdc$height, bmi)
cor.test(cdc$height, bmi)

# Question 8
sum(bmi >= 30)

# Question 9
plot(cdc[1:100, 5], cdc[1:100, 6],
     xlab = "Height (inchs)",
     ylab = "Weight (pounds)")

# Question 10
is_obse <- bmi >= 30
is_male <- cdc$gender == "m"
sum(is_obse & is_male)

