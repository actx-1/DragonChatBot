*Temporary decision base*
## Module Types:
- Network Module
- Dispatch Module
- Control Module
- Core Module

# Network Module
Handles connectivity between each individual service and the modules behind the bot for that service.

# Dispatch Module
Applies logic-based scanning to each message received, in order to determine what functionality should be called upon in response, and sends it onto the correct core module accordingly.

# Control Module
Receives commands from the system operator and manages other modules.

# Core Module
Where all the meat of the bot is.
