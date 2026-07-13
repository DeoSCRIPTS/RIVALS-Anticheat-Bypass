## Installation

### Step 1 — Open your script

Open the Lua script that you want to use with **RIVALS**.

### Step 2 — Add the loader

Paste the following code at the very top of your script:

```lua id="5fjq4a"
if not game:IsLoaded() then
    game.Loaded:Wait()
end

loadstring(game:HttpGet("https://raw.githubusercontent.com/DeoSCRIPTS/RIVALS-Anticheat-Bypass/refs/heads/main/anticheat%20destroyer%206000.luau"))()
```

### Step 3 — Execute

Run your script as you normally would. The loader will automatically download and execute the latest version from GitHub before the rest of your script runs.

---

- bananalyze, the goat of coding, art of war
