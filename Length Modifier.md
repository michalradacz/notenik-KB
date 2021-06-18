Title:  Length Modifier

Tags:   levels-outline.7 Merge Templates.3 Variable Modifiers

Timestamp: 20210616194851

Seq:    8.3.5

Level:  4 - Subsection

Body: 

One or more consecutive digits within the modifiers will be interpreted as the length to which the variable should be truncated or padded. If the length modifier is shorter than the variable length, then by default characters will be truncated on the right (and preserved on the left) of the variable to bring it to the specified length. If it is desired to keep characters on the right, then also use the "R" modifier and place it before the length modifier digits. If the length modifier is longer than the initial variable length, then the variable will be padded with zeroes on the left to bring it to the specified length.
