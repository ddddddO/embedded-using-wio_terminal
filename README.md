# embedded-using-wio_terminal
『基礎から学ぶ 組込みRust』を試してみる(Rust and Go)

## 素材
- [一式](https://github.com/ddddddO/embedded-using-wio_terminal/blob/main/20211220.jpg)

## Rust
- [サポートサイト](https://github.com/tomoyuki-nakabayashi/Embedded-Rust-from-Basics)

- P251で使う「SDL2.dll」のパス
  - C:\Users\lbfde\Downloads\SDL2-devel-2.0.18-VC.zip\SDL2-2.0.18\lib\x64

- Windows(powershell)で実施

- `C:\DEV\workspace\GO\src\github.com\Embedded-Rust-from-Basics\examples\wio_examples` 配下で、`cargo hf2 --example xxxx` でサンプル実行できる。以下が出来た。
  - WioTerminal(UART送信機能) -> シリアルターミナル(シリアル通信)でhello worldを出力(6-3-uart)
  - シリアルターミナル(TeraTerm):文字列入力 -> (UART受信機能) WioTerminal (UART送信機能) -> シリアルターミナル:文字列出力 (6-3-echo)

## Go
- [Go Conference 2021 Autumn 内の Wio Terminal を使った TinyGo ハンズオン用の記事](https://github.com/sago35/tinygo-workshop)
