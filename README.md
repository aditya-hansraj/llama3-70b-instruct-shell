# NVIDIA Chat API Script

This script allows you to send a query to the NVIDIA API and retrieve a response using the `curl` command.

## Prerequisites

- Bash
- `curl` command-line tool

## Usage

1. Save the script to a file, for example, `llama3`.
2. Make the script executable:

    ```bash
    chmod +x llama3
    ```

3. Run the script with your query as an argument:

    ```bash
    ./llama3 "Your query here"
    ```

## Script Details

The script performs the following actions:

1. Takes a query as a command-line argument.
2. Sends a POST request to the NVIDIA API endpoint with the query.
3. Extracts the response content using `grep` and `tr` commands.
4. Outputs the response.

## Example

```bash
./llama3 "What is the weather like today?"
```
## Notes
- Ensure that you replace the Authorization token with a valid token.
- The API model used is [meta/llama3-70b-instruct](https://build.nvidia.com/meta/llama3-70b?snippet_tab=Shell).
- The streaming option is enabled.
