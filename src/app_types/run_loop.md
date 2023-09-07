# Run Loop

**Overview**:  
"Run Loop" apps are CLI applications that maintain an operational loop after initiation. They wait for user input, execute repetitive tasks, or continually produce output until they're explicitly terminated.

**Characteristics**:

- Start and enter a loop.
- Wait for triggers, input, or follow a set pattern of tasks.
- Do not exit unless explicitly asked or in the event of an error.

**Example Apps**:

1. **Server**: Wait for client connections and serve requests.
2. **Log Tailing**: Continually read from a log file and display new entries.
3. **Interactive Shell**: Wait for user commands, execute them, and then wait for the next command.

For a closer look at the IO patterns inherent to "Run Loop" apps, please visit the [IO Types section](../io_types/run_loop/README.md).
