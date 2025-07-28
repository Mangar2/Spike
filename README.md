# Spike
The Spike chess engine was developed in the early 2000s and achieved several successes in international computer chess tournaments, most notably winning first place at the Chess960 World Championship in Mainz in 2005. The last official version, 1.4, was released in early 2011 and, for the first time, included a free multiprocessor version supporting up to 12 CPUs.

The now available version 1.4.1 plays almost identically to version 1.4. However, its source code has been updated: for example, the legacy multi-threading code was ported to C++20 to improve portability. As a result, Spike 1.4.1 is available for Windows, Linux, and macOS, compiled using clang++ supporting up to 32 CPU.

In addition to roughly 15% more performance, it is now ideal for chess engine testing. Features such as the internal opening book and learning are disabled by default, so tournaments can be run out-of-the-box without additional configuration.

Spike 1.4.1 also adheres more closely to the specifications of chess engine protocols (UCI, Winboard). For instance, at search depth 0, "nm" is no longer shown as part of the principal variation, and KBKN (king and bishop vs. king and knight) is no longer reported as a draw under Winboard.

In short: Spike 1.4.1 is a freely available chess engine with a storied past – now modernized and cross-platform.
