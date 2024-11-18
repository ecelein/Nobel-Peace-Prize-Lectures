## Nobel Peace Prize Lectures (2013-2023)

This dataset contains the Nobel Peace Prize Lectures awarded for the last 10 years (2013-2023).

#### Target audience

- Any individual who is interested in analyzing Nobel Peace Prize lectures for linguistic, cultural, or historical insights.

#### Selection criteria

- Lectures must be delivered by Nobel Peace Prize laureates between 2013 and 2023.
- Only fully available, official transcripts were considered.
  Texts were sourced directly from the official Nobel Prize website: https://www.nobelprize.org/prizes/lists/all-nobel-peace-prizes/

#### Data collection process

- Manual extraction of text from official source (Nobel Prize website).
- Texts were saved in a consistent format (.txt) with standardized file names for easy referencing.

#### Annotations

- Each text was annotated with corresponding metadata (e.g., year, laureate name, place of birth/foundation, and prize share).
- NLP preprocessing (e.g., tokenization, lemmatization, and named entity recognition) was applied for further linguistic analysis.

## Format of the files in the corpus

Below are the data columns and their descriptions that can be found in the "final_nobel_lectures.csv" file.

| Column Name                        | Description                                        |
| ---------------------------------- | -------------------------------------------------- |
| Filename                           | The original filename of the .txt file             |
| Prize Laureate                     | The person or organization that received the prize |
| Year Awarded                       | Year in which the prize was awarded                |
| Place of Birth/Place of Foundation | Place of which the person/organization originated  |
| Date of Birth/Date of Foundation   | Date on which the person/foundation came to being  |
| Prize Share                        | Share amount of prize                              |
| Document                           | The original text as it appears on the .txt file   |
| Doc                                | Doc objects                                        |
| Tokens                             | Tokenization applied                               |
| Lemmas                             | Lemmatization applied                              |
| POS                                | Part-of-speech tagging applied                     |
| Proper_Nouns                       | Proper nouns that are extracted                    |
| Named_Entities                     | Named Entities that are tagged                     |
| NE_Words                           | Words and phrases identified as Named Entities     |

⚠️ **Note 1**: Some 'Place of Foundation' entries are missing since they are international organizations that do not have a distinct center.

⚠️ **Note 2**: The data does not include 2024 lecture even though the prize was awarded, because the lecture did not take place yet.
