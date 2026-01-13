**CommandLock** is a lightweight and focused plugin designed to block command execution and tab-completion leaks without heavy group systems, complex inheritance trees or unnecessary overhead.

_If you are tired of over-engineered solutions just to hide commands, **CommandLock is built for you.**_

# ✨ Why CommandLock?
Most command-hiding plugins try to do everything — groups, priorities, inheritance — and end up being **bloated, hard to configure and expensive.
**
**CommandLock does one thing extremely well:
It prevents players from discovering or executing commands they shouldn’t know exist.**

# Core Features
- ✔ Block tab-completion suggestions for unauthorized commands
- ✔ Block command execution with optional custom messages
- ✔ Works on legacy and modern servers (1.7 – 1.21)
- ✔ Extremely lightweight — minimal listeners, no heavy processing
- ✔ Group systems, inheritance, no complex permission trees
- ✔ Simple configuration
- ✔ Anti Spy Hacks (Spy Protect)
- ✔ Designed for hubs, lobbies and survival servers
- ✔ Java 8 compatible (perfect for 1.8.8 servers)

**Dependencies**
[ProtocolLib (required)](https://www.spigotmc.org/resources/protocollib.1997/)
# ☕ Java Compatibility (IMPORTANT)

CommandLock depends on **ProtocolLib**.
If you are running **Java 8**, you **MUST** use a ProtocolLib version **≤ 5.3.0.**
Using newer ProtocolLib versions on Java 8 **will cause class loading errors and crashes.**

**Recommended setup for Java 8 servers**
- > Java: 8
- > ProtocolLib: 5.3.0 or lower
- > Minecraft: 1.7 – 1.12 (and some 1.13+ legacy setups)
  
**Recommended setup for modern servers**
- > Java: 17+
- > ProtocolLib: latest stable
- > Minecraft: 1.16 – 1.21

COMMANDS
commandlock reload Reloads the config.yml
commandlock help Additional information
commandlock info Retrieves information about the player, like the applied group and inherited groups
commandlock updatecheck Checks updates
PERMISSIONS
commandlock.reload | Reloads the config.yml
commandlock.group.<group> | To apply a specific group to an user
commandlock.info
commandlock.update
