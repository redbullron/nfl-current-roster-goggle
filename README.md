# NFL Current Roster Goggle 🏈

A Brave Search Goggle designed to prioritize current NFL roster information and filter out outdated historical data.

## 🎯 Purpose

This Goggle solves the common problem of getting outdated NFL roster information in search results. It specifically:

- **Boosts** official NFL sources and trusted sports sites
- **Prioritizes** 2025 season content and current rosters
- **Downranks** historical content from previous seasons
- **Excludes** unreliable sources like Wikipedia and fan sites
- **Emphasizes** official team websites and current player status

## 🚀 How to Use

### Step 1: Get the Goggle URL
Copy this URL for the Goggle file:
```
https://raw.githubusercontent.com/redbullron/nfl-current-roster-goggle/main/nfl-current-roster.goggle
```

### Step 2: Add to Brave Search
1. Go to [Brave Search Goggles Submission](https://search.brave.com/goggles/create)
2. Paste the URL above
3. Submit for validation

### Step 3: Use in n8n
1. In your n8n Brave Search node
2. Find the "Goggles" parameter
3. Add the URL: `https://raw.githubusercontent.com/redbullron/nfl-current-roster-goggle/main/nfl-current-roster.goggle`

## 🎯 What This Goggle Does

### ✅ BOOSTS (Higher Rankings)
- **Official Sources**: NFL.com, ESPN.com, PFF, FantasyPros
- **2025 Season Content**: Heavily prioritizes current season
- **Official Team Sites**: All 32 NFL team websites
- **Current Terms**: "current roster", "active roster", "depth chart"
- **Recent Player Moves**: "signed", "traded", "activated"

### ⬇️ DOWNRANKS (Lower Rankings)
- **Previous Seasons**: 2024, 2023, 2022, etc.
- **Historical Terms**: "former", "retired", "career stats"

### ❌ EXCLUDES (Removes from Results)
- **Unreliable Sources**: Wikipedia, Fandom, fan blogs
- **Archived Content**: Wayback Machine, cached pages
- **User-Generated**: Reddit, Quora

## 🔧 Technical Details

- **Version**: 1.0.0
- **License**: MIT
- **Format**: Brave Search Goggles DSL
- **Rules**: 80+ filtering and ranking rules

## 🐛 Issues or Improvements

Found a problem or want to suggest improvements? 
[Open an issue](https://github.com/redbullron/nfl-current-roster-goggle/issues)

## 📝 Example Use Cases

Perfect for:
- ✅ Getting current NFL team rosters
- ✅ Finding active player statistics
- ✅ Checking current fantasy football information
- ✅ Avoiding outdated player information (like Stefon Diggs on Bills)

## 🤝 Contributing

Feel free to submit pull requests to improve the Goggle rules or add new trusted sources!

---

**Created for accurate NFL roster information in automated workflows** 🎯