# TSMemory ver0.4.0.1
TSMemory ver0.4.0.1
H.264（AVC) / H.265(HEVC) 対応版

前バージョンを元に改修。前バージョンはこちら（https://github.com/norick-works/TSMemory-Kai）

TSMemoryがmpeg2-tsのみの対応だったがH264、H265も読み込めるように改修(理論上８Kも読み込める）
非プログラマーがClaudeおよびGPTを使って改修のためバグも出てくると思いますが、
TVTestについて語るスレもしくはXまでご連絡ください。

【変更点】
TVTestsrcからL-SMASHを利用（H264およびH265に対応すべく）
（ソースの修正箇所：tsselector.h  tsslector.cpp  tsmemory.cpp)

【削除】
TVtestsrc

（注意）
AviUtl32bitでは最大画像サイズを指定してもエラーにて表示できず、
AviUtlExEdit2では大幅な改修が必要なため未対応。

