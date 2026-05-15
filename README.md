# @time/chrono — Date and Time Library for Zeta (High-Level)

Auto-converted from [chrono](https://crates.io/crates/chrono) v0.4.44 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Features
- **NaiveDate/NaiveTime/NaiveDateTime** — date/time without timezone
- **DateTime<Tz>** — date/time with timezone (UTC, Local, FixedOffset)
- **TimeZone** — comprehensive timezone handling with DST
- **Duration** — signed duration (nanoseconds to weeks)
- **Formatting/parsing** — `format!`, `parse_from_str`, ISO 8601, RFC 2822, RFC 3339
- **Arithmetic** — add durations, compute time differences, weekday/month calculations
- **Serde** — serialization via `@data/serde`

## Usage
```zeta
use @time/chrono::{Utc, DateTime};

let now: DateTime<Utc> = Utc::now();
println!("{}", now.format("%Y-%m-%d %H:%M:%S"));
```

## Stats: ~16,578 lines, 0 unsupported items

## License: MIT