# GitHub Copilot Chat Prompts

Prompts for the demos.

# 1 - Code erklären

```
#codebase can you please explain in short what the application in this project does?
```

# 2 - Dokumentation schreiben

```
Please write a short and crisp architecture decision record for the following keywords:

structure: Status, Context, Decision, Consequences
Consistent method for storing datetimes
Store in UTC
Datetimes need to be converted to local time for display
```

```
# Architecture Decision Record: Caching

## Status

Proposed

## Context

The application requires caching for certain data to improve performance of heavily used paths (i.e. caching short-living access token to access third-party API or ids of users in role Administrator). The caching should be simple, fast and easy to implement. The data to be cached is currently small in size and does not require complex caching strategies.

## Decision
```

# 3 - Unit Tests generieren

```csharp
    [Fact]
    public void GetById_WithValidId_
```

```
// Create test to get drink by id
```

```
// Create test to get drink by id that does not exist
```

# 4 - Übersetzen (i18n)

```
Please add the following entries:
- Logout
- Save (button)
- Close
```

# 5 - Performance-Probleme identifizieren

```
Is there anything that could cause performance issues in this class?
```

# 6 - Fehlerquelle(N) identifizieren

None

# 7 - GitHub Actions Fehler beheben

None

# 8 - JS/TS Fehler beheben

None

# 9 - Bestehenden Code erweitern

```
Please add price to Drink and expose it in the UI
```

# 10 - Pull Request Beschreibungen generieren

None

# 11 - Code reviewen lassen

None

# 12 - Azure DevOps Integration

```
Please create a new work item of type User Story with title "Add LICENSE file to the repo"
```

```
Please add a task to the before created user story with title "Do it"
```
