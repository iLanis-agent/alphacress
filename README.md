# Alphacress 1.0 TEST
Native Android letter-to-digit addition puzzles. Android8+ min26/target35. Package com.gg007.alphacress.

## Rules
Known decimal cryptarithm adaptation, not a word puzzle. Six letters A-F each stand for a different digit from 0-9. The same letter always has the same digit throughout the equation. Two three-digit numbers add to one four-digit number. No number may begin with zero. Two gold letter assignments are fixed; choose a teal letter and a digit for each of the four unknown letters. Tap CHECK ADDITION after filling them. Every puzzle has exactly one solution with its gold clues. Clear removes the selected assignment; undo/reset, twelve levels, saved palette and optional digit preview. Duplicate digits and leading zeros are rejected at check time, not blocked while entering.

## Download and status
https://mega.co.nz/#!ZMcgERIb!vB9QDl_p5VAY0KrEkxm7rw4olkaseSDqfTSFLjLM3_c
APK 20974 bytes; SHA256 262f805f0b35c1ea531f742f8dbcb107cb7096a583e02c4f7e384c143ec6b159. Original certificate SHA2561651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions; original GG007 icon unchanged. Anonymous downloaded bytes match.

## Checks
Seed 891110 generates twelve different six-letter equation patterns, each with two fixed clues and a unique solution. Independent Java right-to-left column/carry oracle compared against production whole-number evaluation on all 1000000 six-digit maps per puzzle, including repeats and leading zeros: 12000000 exact verdict comparisons. Plus 120000 malformed/range checks. Every puzzle has exactly one accepted assignment. Fixed/no-selection/bounds/incomplete/explicit-check/solved locks, clear/undo/replay/reset pass. Actual drawing-adapter letter/digit/check taps solve all twelve; menus/privacy/next/levels/saved palette/digit preview/completion pass. Eight drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
All 220 prior studio and 803 legacy descriptions were reviewed. Matchcress transfers one physical digit segment while keeping plus and equals fixed; Factorcress fills a 1-4 multiplication Latin table; Make24 combines four supplied numbers and operators. Alphacress instead assigns one shared injective letter-to-digit substitution across a fixed decimal addition, enforcing place values, carries and nonzero leading digits. No matching factory mechanic found. Known cryptarithm concept, not globally new. Original generated equations, code and drawings; no published word equations, layouts or solver code copied. Six fully read sources include encyclopedia, educational course, university-hosted puzzle author, independent primer and technical explanations. Some sources reserve alphametic for meaningful words; these A-F equations are cryptarithms, not meaningful-word alphametics. No historical invention-date claims are used.

## Build and tests
JDK17/AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/alpha-test src/com/gg007/alphacress/Board.java BoardTest.java then java -Xmx256m -cp /tmp/alpha-test com.gg007.alphacress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your private signing material. No signing secret is included. adapter/android contains the Java2D drawing adapter used with AlphaAdapterTest.java, not an Android runtime.

## Privacy and branding
Alphacress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, digit preview and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon, studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative221-card studio and publishing fragments privately preserved:
https://files.instinct.com/hzkj9xhqlyfe-alphacress-source-archive
https://github.com/iLanis-agent/alphacress holds README only, full Git source pending. Existing three studio includes and Pages settings untouched. Both sites verified separately.

## Rule sources
https://www.futurelearn.com/info/courses/recreational-math/0/steps/43523
http://cryptarithms.awardspace.us/primer.html
https://en.wikipedia.org/wiki/Verbal_arithmetic
https://www.math.uni-bielefeld.de/%7esillke/PUZZLES/ALPHAMETIC/alphametic-mike-keith.html
https://algorithm.tamnd.com/cryptarithmetic-puzzle/
http://mathstorehouse.kr/en/archives/mathematics/others/mathematical-puzzle/1568
