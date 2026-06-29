# TSMemory ver0.4.0.1
TSMemory ver0.4.0.1
H.264（AVC) / H.265(HEVC) 対応版

前バージョンを元に改修。前バージョンはこちら（https://github.com/norick-works/TSMemory-Kai）

TSMemoryがmpeg2-tsのみの対応だったがH264、H265も読み込めるように改修(理論上８Kも読み込める）
非プログラマーにつきClaudeおよびGPTを駆使しての改修。
そのためバグも出てくると思いますが、TVTestについて語るスレもしくはXまでご連絡ください。

【注意】
このバージョンからL-SMASHを利用のため事前に導入をお願いします。
利用中のtvtestに対して同じbitでビルドをお願いします。
基本的にはTSMemory.tvtpとCaptureUtil.aufの入替だけど問題ないはずです。

【変更点】
TVTestsrcからL-SMASHを利用（H264およびH265に対応すべく）
（ソースの修正箇所：tsselector.h  tsslector.cpp  tsmemory.cpp)

【削除】
TVtestsrc

最後に...
８Kのキャプチャーについて
AviUtl32bitでは最大画像サイズを指定してもエラーにて表示できず、
またAviUtlExEdit2では既存のものでは未対応のため大幅な改修が必要。
