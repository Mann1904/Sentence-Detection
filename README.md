# Sentence-Detection
The task of sentence boundary detection is to identify sentences within a text. Many natural language processing tasks take a sentence as an input unit, such as part-of-speech tagging, dependency parsing, named entity recognition or machine translation.

## Input Text
A California woman who vanished in Utah’s Zion National Park earlier 
this month was found and reunited with her family, 
officials said Sunday. Holly Suzanne Courtier, 38, was located within the park after a visitor 
saw her and alerted rangers, the National Park Service said in a statement.
Additional details about how she 
survived or where she was found were not immediately available. In the statement, Courtier’s relatives said they were “overjoyed” that she’d been found.
Courtier, of Los Angeles, disappeared after a private shuttle dropped her off on Oct. 6 at the Grotto park area 
inside the 232-square-mile national park. She was scheduled to be picked up later that 
afternoon but didn't show up, park officials said. The search included K-9 units and federal, 
state and local rescue teams. Volunteers also joined the effort.


## Detected Sentences using Spark NLP SentenceDetectorDL
0. A California woman who vanished in Utah’s Zion National Park earlier this month was found and reunited with her family, officials said Sunday.
1. Holly Suzanne Courtier, 38, was located within the park after a visitor saw her and alerted rangers, the National Park Service said in a statement.
2. Additional details about how she survived or where she was found were not immediately available.
3. In the statement, Courtier’s relatives said they were “overjoyed” that she’d been found.
4. Courtier, of Los Angeles, disappeared after a private shuttle dropped her off on Oct. 6 at the Grotto park area inside the 232-square-mile national park.
5. She was scheduled to be picked up later that afternoon but didn't show up, park officials said.
6. The search included K-9 units and federal, state and local rescue teams.
7. Volunteers also joined the effort.

## Detected Sentences using Spacy Sentence Detection
0. A California woman who vanished in Utah’s Zion National Park
1. earlier this month was found and reunited with her family, officials said Sunday.
2. Holly Suzanne Courtier, 38, was located within the park after a visitor saw her and alerted rangers, the National Park Service said in a statement.
3. Additional details about how she survived or where she was found were not immediately available.
4. In the statement, Courtier’s relatives said they were “overjoyed” that she’d been found.
5. Courtier, of Los Angeles, disappeared after a private shuttle dropped her off on Oct. 6 at the Grotto park area inside the 232-square-mile national park.
6. She was scheduled to be picked up later
7. that afternoon
8. but didn't show up, park officials said.
9. The search included K-9 units and federal, state and local rescue teams.
10. Volunteers also joined the effort.


