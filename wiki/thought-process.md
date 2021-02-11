# My Thought Process
## Understand requirements & outcomes
- Requirements - 3 charts (bar, pie, and donut)
  
For the bar chart
| categories | numberOfCards |
| ---------- | ------------- |
| Cups       | x             |
| Swords     | y             |
| Pentacles  | z             |
| Wands      | lmao          |


For the pie chart
| categories   | percentageOfCards |
| ------------ | ----------------- |
| Major Arcana | x%                |
| Minor Arcana | y%                |

For the donut chart
| categories | percentageOfCards |
| ---------- | ----------------- |
| Upright    | x%                |
| Reversed   | y%                |

## Understand the data
- Keep in mind the coding of the cards
  - Major Arcana cards have a m- prefix. So, The Fool would be m-fool
  - Minor Arcana cards have the format <number>-<suit>.
    - <number> runs from 1 (Ace) through k (King) with Knight using the letter n
    - <suit> takes after the suit's first letter - Cups is c, Swords is s, and so on
    - So the Knight of Wands would be n-w while the Ace of Wands would be 1-w
  - Reversed cards have a -r suffix, regardless of Major or Minor Arcana. So, The Magician Reversed would be m-magician-r
  - Every letter is in lowercase :D

- For each file, I only need the front part ("frontmatter"/YAML) - and specifically only the list of cards


## Plan of Action
```python
# Read the files (how to read a file?)
  # For each file, I need the front part - and specifically only the list of cards (how to get the frontmatter only?)

  # Need to add it to ultimate list of cards and/or start producing the tables right away (categorise from the beginning)

# Ultimately, I need to categorise the cards that I have (using what data type?)
# Use a library to draw the graphs based on the different tables that I have (which library?)
```
