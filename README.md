# NVIDIA Chat API Script

This script allows you to send a query to the NVIDIA API and retrieve a response using the `curl` command.

## Prerequisites

- Bash
- `curl` command-line tool

## Usage

1. Save the script to a file, for example, `nvidia_chat.sh`.
2. Make the script executable:

    ```bash
    chmod +x nvidia_chat.sh
    ```

3. Run the script with your query as an argument:

    ```bash
    ./nvidia_chat.sh "Your query here"
    ```

## Script Details

The script performs the following actions:

1. Takes a query as a command-line argument.
2. Sends a POST request to the NVIDIA API endpoint with the query.
3. Extracts the response content using `grep` and `tr` commands.
4. Outputs the response.

## Example

```bash
./nvidia_chat.sh "What is the weather like today?"
