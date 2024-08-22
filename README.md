# instructor-helpers

Various helper functions for using [instructor](https://jxnl.github.io/instructor/).

Functions available are:
 - simple_completion - A wrapper to make calling instructor easy, either as a simple string or using a Pydantic result class
 - get_instructor_client - Returns a constructor client, either using an OpenAI model or a local Ollama model
 - chunk_list - takes a list of strings and returns another list of strings with the original strings concatenated into chunks

See `example.ipynb` for an example of using simple_completion