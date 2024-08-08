# ARC Prize 2024 on Kaggle

https://www.kaggle.com/competitions/arc-prize-2024/overview

How to load input and save output:
[minimal_submission by ironbar](https://www.kaggle.com/code/ironbar/minimal-submission)

## Submission file format

The file must be saved in the current dir, as: `"submission.json"`

Puzzles can have multiple tests.
Each test can have 2 attempts at a solution.

```json
{
	...
	"3345333e": [
    		{"attempt_1": [[0, 0], [0, 0]],"attempt_2": [[0, 0], [0, 0]]}
	],
	"3428a4f5": [
   		{"attempt_1": [[0, 0], [0, 0]],"attempt_2": [[0, 0], [0, 0]]}, 
    		{"attempt_1": [[0, 0], [0, 0]],"attempt_2": [[0, 0], [0, 0]]}
	],
	...
}
```

## challenges.json file format

The 100 unseen tasks is found in the file: `"/kaggle/input/arc-prize-2024/arc-agi_test_challenges.json"`

Puzzle with multiple tests.

The `"test"` pairs have no `"output"`, since this is what is to be predicted.

```json
{
    ...
    "aabbccdd": {
        "test": [
          {"input": [[7, 7], [0, 7]]},
          {"input": [[8, 8], [7, 8]]}
        ], 
        "train": [
            {"input": [[5, 5], [0, 5]], "output": [[0]]}, 
            {"input": [[5, 5], [1, 5]], "output": [[1]]}, 
            {"input": [[5, 5], [3, 5]], "output": [[3]]}
        ]
    }, 
    ...
}
```

## solutions.json file format

Puzzle with multiple tests.

```json
{
  ...
  "3428a4f5": [
    [[3, 0, 3, 0, 3], [0, 0, 0, 3, 0], [0, 0, 0, 0, 3], [3, 0, 0, 3, 3], [3, 3, 0, 3, 0], [0, 3, 0, 0, 0]], 
    [[0, 3, 3, 0, 3], [3, 3, 0, 3, 0], [0, 0, 3, 0, 0], [0, 0, 3, 3, 0], [3, 3, 0, 3, 3], [0, 3, 3, 0, 3]]
  ], 
  ...
}
```
