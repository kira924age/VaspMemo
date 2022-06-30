# VaspMemo

`VASP` に関するメモを残す Repository.

## INPUT

`VASP` で計算を行う場合カレントディレクトリに以下の４つの入力ファイルを用意する.

- POSCAR
  - 計算対象の系の結晶構造のデータ. 原子の種類や座標を記述
- INCAR
  - 計算条件を記述
- KPOINTS
  - Bloch vectors (k点) を記述
  - 積分計算をするときのメッシュの細かさを設定できる
- POTCAR
  - 各原子の擬ポテンシャルを記述
  - GGA, LDA, PBE などから物質に応じて適切なものを選ぶ
