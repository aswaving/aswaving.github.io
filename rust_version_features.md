# Rust language feature feature introductions

## 1.13 (November 2016)
- `?` operator

## 1.28 (August 2018)
- `#[repr(transparent)]`
- `NonZeroUsize`, `NonZeroU128`, `NonZeroU64`, `NonZeroU32`, `NonZeroU16`, `NonZeroU8`
- `Iterator::step_by`, `iter::repeat_with`

## 1.30 (October 2018)
- procedural macros are available
- raw identifiers for reserved keywords `r#`, e.g. `r#for`
- `#[used]`
- `#[panic_handler]`
- `str::trim_end_matches`, `str::trim_end`, `str::trim_start_matches`, `str::trim_start`

## 1.31 (December 2018)
- 2018 edition

## 1.32 (January 2019)
- several API functions are now `const` functions: e.g., `char::is_ascii`
- `to_be_bytes`, `to_le_bytes` for all numerical types

## 1.36 (July 2019)
- `mem::MaybeUninit`

## 1.42 (March 2020)
- `matches` macro
