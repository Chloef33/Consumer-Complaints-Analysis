# Complaint Analysis

## Cleaning the Data
Looking at the data there was very little cleaning that we needed to do. We just made all blank cells n/a by using an if statement. Also changed the zip code column to be numeric. 

`complaints$ZIP.code <- as.numeric(complaints$ZIP.code)`
`complaints$Consumer.consent.provided. <- ifelse(complaints$Consumer.consent.provided. == "", "N/A",complaints$Consumer.consent.provided.)`
