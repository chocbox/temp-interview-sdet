# Senior QA — API Testing Exercise

Test the [Deck of Cards API](https://deckofcardsapi.com/) through the provided `DeckOfCardsApiClient`.

**Prerequisites:** .NET 8 SDK, internet access

## Setup

```bash
dotnet restore
dotnet build
dotnet test
```

Expect **3 passing** example tests and **4 skipped** exercises.

## Your task

Implement the skipped tests in `tests/DeckOfCards.Tests/Exercises/CandidateExercises.cs`. Remove each `Skip` when done.

Copy patterns from `tests/DeckOfCards.Tests/Examples/`. Use `DeckOfCardsApiClient` — read its methods and the [API docs](https://deckofcardsapi.com/).

**The client may have bugs.** Write tests against expected API behavior. If a test fails, document what you found.

| # | Area |
|---|------|
| 1 | Unshuffled deck — first drawn card |
| 2 | Partial deck — AS, 2S, KS, AD, 2D, KD, AC, 2C, KC, AH, 2H, KH |
| 3 | Multi-deck card count |
| 4 | Pile workflow |
