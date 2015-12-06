#

## Goのライブラリ現状

* 現状Golibraryは「最新」のライブラリしか使えない.(gem みたいなものはない)
* libraryが破壊的な仕様変更をしていないかどうかをチェックするツールがほしい

## APIの変更

## Gompatible

```
gompad rev..rev repository名
```

### 実装

+ 標準パッケージで実装している

#### go/types

* 色々とってくるのがめんどいところがある．
  ```x/tools/go/loader``` を使うと便利

#### go/build

#### go-vcs

* レポジトリとリビジョンを指定すれば，そのファイルツリーをvirtual filesystemとして取ってこれる
