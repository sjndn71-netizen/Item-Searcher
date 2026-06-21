<div align="center">

# ðŸ” Military Tycoon Trade Scanner

**Automatically hops servers searching for a specific vehicle at your price â€” hands free.**

![Private](https://img.shields.io/badge/status-private-red?style=for-the-badge)
![Roblox](https://img.shields.io/badge/game-Military%20Tycoon-blue?style=for-the-badge)
![Lua](https://img.shields.io/badge/language-Lua-purple?style=for-the-badge)

</div>

---

## âš¡ Loadstring

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/sjndn71-netizen/Item-Searcher/refs/heads/main/Item%20Searcher"))()
```

> **Put this in your executor's auto-execute folder** so it keeps running after each server hop.

---

## ðŸ› ï¸ What It Does

- Scans the trade shop in every server for a vehicle you specify
- Hops to a new public server automatically if it's not found
- Keeps going until it finds a match â€” no babysitting required
- Walks your character directly to the seller when found
- Remembers your search across server hops so you never have to retype it

---

## ðŸŽ® How To Use

| Step | Action |
|------|--------|
| 1 | Run the loadstring above in your executor |
| 2 | First launch shows a warning â€” read it, type `I UNDERSTAND` to unlock |
| 3 | Enter the **vehicle name** (partial names work, e.g. `sky` finds `Skyhammer`) |
| 4 | Optionally set a **min and max price** in diamonds |
| 5 | Press **Auto Loop** and let it run |
| 6 | Press **Stop** at any time to cancel â€” stops walking immediately |

---

## ðŸ’Ž Price Range

You can filter by a price window instead of an exact number.

- Set **Min** to `40000` and **Max** to `42000` â†’ matches anything priced 40kâ€“42k
- Leave both blank â†’ matches any price
- Supports shorthand: `40k` = `40000`

---

## ðŸ”’ Notes

- **Private** â€” not for public release
- Requires an executor that supports `writefile` / `readfile` for state persistence
- Built with [Rayfield UI](https://github.com/SiriusSoftwareLtd/Rayfield)
