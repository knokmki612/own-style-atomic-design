# オレオレ Atomic Design

## Atom

最小の粒度の UI コンポーネント

`<button></button>` あるいは `<input>` のように、UI と操作の対象 (onClick とか onChange とかのイベントが発生するような) が 1 対 1 の関係であるもの

## Molecules

Atom もしくは Molecules を組み合わせたもの、もしくは UI と操作の対象が n 対 n のもの

しかし、実際に使われる際には Organisms に依存するような、単体では画面構成において独立しない粒度のもの

## Organisms

Atom もしくは Molecules もしくは Organisms を組み合わせたもの、もしくは UI と操作の対象が n 対 n のもの

かつ、画面構成において独立した粒度のもの

## Templates

Atom もしくは Molecules もしくは Organisms を組み合わせたもの

かつ、一画面そのものの粒度のもの
