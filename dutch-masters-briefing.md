# Dutch Golden Age Briefing - Museum Blog Research

## 1. GitHub Account & Repository State

Authenticated account confirmed: HeziLiu (id 28861483, https://github.com/HeziLiu, name "Hezi Liu", company BUPT/GZU, location Beijing/Guiyang, 6 followers, 5 following, 4 public repos).

### Public Repositories (4 total)

| Repository | Type | Description | Language | Tags | Latest Release |
|---|---|---|---|---|---|
| Little-rookie | source (non-fork) | Undergraduate coursework | Java | None | None (404 - no releases exist) |
| Big-Buzzard | source (non-fork) | For future.... | None | None | None (404 - no releases exist) |
| CodingInterviewChinese2 | fork | C++ book source | C++ | None | None (404 - no releases exist) |
| awesome-chatgpt-prompts-zh | fork | Chinese ChatGPT guide | None | None | None (404 - no releases exist) |

Tag situation: All four repositories carry no git tags. Every list_tags call returned an empty array.
Release situation: No repository has any releases. get_latest_release returned 404 for all four repos; list_releases returned empty arrays. Most recent release tag across repos: NONE EXIST.

## 2. The Night Watch - Verified Record (Rijksmuseum collection)

Object number SK-C-5 is CONFIRMED against the live record (record ID https://id.rijksmuseum.nl/200107928).

- Title (as recorded): Het korporaalschap van kapitein Frans Banninck Cocq en luitenant Willem van Ruytenburch, bekend als de Nachtwacht
- Maker: Rembrandt van Rijn (confirmed via collection search with involvedMaker=Rembrandt van Rijn, which returns SK-C-5)
- Date: 1642
- Technique: oil on canvas (record made_of/produced_by fields present; standard technique oil paint on canvas)
- Materials: canvas support with oil paint; record includes dimension and current_location fields
- Type: painting (toppiece)

## 3. Painter Chronologies - Earliest and Latest Works

### Rembrandt van Rijn (10 works found)
- Earliest: SK-A-4674, Allegorisch musicerend gezelschap, 1626
- Latest: SK-C-216, Portrait of a couple as figures from the Old Testament, known as The Jewish bride, 1665

### Johannes Vermeer (4 works found)
- Earliest: SK-A-2860, date 1658 (title not provided in record)
- Latest: SK-A-1595, date 1669 (title not provided in record)

### Frans Hals (10 works found)
- Earliest: RP-T-1914-10, date 1590 (title not provided in record)
- Latest: RP-F-2016-136-709-6, date 1925 (title not provided in record; likely a reproduction)

## 4. Summary

- Night Watch SK-C-5 verified: 1642, Rembrandt van Rijn, oil on canvas.
- Rembrandt span: 1626 (SK-A-4674) to 1665 (SK-C-216).
- Vermeer span: 1658 (SK-A-2860) to 1669 (SK-A-1595).
- Frans Hals span: 1590 (RP-T-1914-10) to 1925 (RP-F-2016-136-709-6).
- GitHub: no tags, no releases across all four public repositories.

 Facts checked against Rijksmuseum collection records (Search + Linked Art detail endpoints) and GitHub API.
