# Systematic Swift

[https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)

## 章立て
 - 基本 / The Basics
 - 基本的な演算子 / Basic Operators
 - 文字列と文字 / Strings and Characters
 - コレクション型 / Collection Types
 - 制御構文 / Control Flow
 - 関数 / Functions
 - クロージャ / Closures
 - 列挙型 / Enumerations
 - 構造体とクラス / Structures and Classes
 - プロパティ / Properties
 - メソッド / Methods
 - 添字 / Subscripts
 - 継承 / Inheritance
 - 初期化 / Initialization
 - 終了処理 / Deinitialization
 - オプショナルチェイニング / Optional Chaining
 - エラー処理 / Error Handling
 - 型キャスト / Type Casting
 - ネストした型 / Nested Types
 - エクステンション / Extensions
 - プロトコル / Protocols
 - ジェネリクス / Generics
 - 自動参照カウント / Automatic Reference Counting
 - メモリ安全 / Memory Safety
 - アクセス制御 / Access Control
 - 応用的な演算子 / Advanced Operators

## [基本 / The Basics](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)
 -  定数と変数 / Constants and Variables
   - 定数と変数の定義 / Declaring Constants and Variables
   - 型アノテーション / Type Annotations
   - 定数と変数の命名 / Naming Constants and Variables
   - 定数と変数の出力 / Printing Constants and Variables
 -  コメント / Comments
 -  セミコロン / Semicolons
 -  整数型 / Integers
   - 整数型の上限と下限 / Integer Bounds
   - Int型 / Int
   - UInt型 / UInt
 -  浮動小数点型 / Floating-Point Numbers
 -  型安全と型推論 / Type Safety and Type Inference
 -  数値リテラル / Numeric Literals
 -  数値の型変換 / Numeric Type Conversion
   - 整数型の変換 / Integer Conversion
   - 整数型と浮動小数点型の変換 / Integer and Floating-Point Conversion
 -  型エイリアス / Type Aliases
 -  Bool型 / Booleans
 -  タプル型 / Tuples
 -  オプショナル型 / Optionals
   - nil / nil
   - if文と強制アンラップ / If Statements and Forced Unwrapping
   - オプショナルバインディング / Optional Binding
   - 暗黙的アンラップ型 / Implicitly Unwrapped Optionals
 -  エラーハンドリング / Error Handling
 -  アサーションと前提条件 / Assertions and Preconditions
   - アサーションによるデバッグ / Debugging with Assertions
   - 前提条件の強調 / Enforcing Preconditions

## [基本的な演算子 / Basic Operators](https://docs.swift.org/swift-book/LanguageGuide/BasicOperators.html)
 -  用語 / Terminology
 -  代入演算子 / Assignment Operator
 -  算術演算子 / Arithmetic Operators
   - 剰余演算子 / Remainder Operator
   - 単項マイナス演算子 / Unary Minus Operator
   - 単項プラス演算子 / Unary Plus Operator
 -  複合代入演算子 / Compound Assignment Operators
 -  比較演算子 / Comparison Operators
 -  三項演算子 / Ternary Conditional Operator
 -  nil合体演算子 / Nil-Coalescing Operator
 -  範囲演算子 / Range Operators
   - 閉区間演算子 / Closed Range Operator
   - 半開区間演算子 / Half-Open Range Operator
   - 片側区間演算子 / One-Sided Ranges
 -  論理演算子 / Logical Operators
   - 論理NOT演算子 / Logical NOT Operator
   - 論理AND演算子 / Logical AND Operator
   - 論理OR演算子 / Logical OR Operator
   - 論理演算子の結合 / Combining Logical Operators
   - 明示的な括弧 / Explicit Parentheses

## [Strings and Characters](https://docs.swift.org/swift-book/LanguageGuide/StringsAndCharacters.html)
 -  文字列リテラル / String Literals
   - 複数行の文字列リテラル / Multiline String Literals
   - 文字列リテラル内の特殊文字 / Special Characters in String Literals
 -  空文字での初期化 / Initializing an Empty String
 -  文字列の変更可否 / String Mutability
 -  文字列は値型 / Strings Are Value Types
 -  文字を扱う / Working with Characters
 -  文字列と文字の連結 / Concatenating Strings and Characters
 -  文字列の補間 / String Interpolation
 -  ユニコード / Unicode
   - Unicodeスカラ値 / Unicode Scalar Values
   - 拡張書記素クラスタ / Extended Grapheme Clusters
 -  文字数を数える / Counting Characters
 -  文字列のアクセスと変更 / Accessing and Modifying a String
   - 文字列のインデックス / String Indices
   - 挿入と削除 / Inserting and Removing
 -  部分文字列 / Substrings
 -  文字列の比較 / Comparing Strings
   - 文字列と文字の同一性 / String and Character Equality
   - 接頭辞と接尾辞の同一性 / Prefix and Suffix Equality
 -  文字列のユニコード表現 / Unicode Representations of Strings
   - UTF-8表現 / UTF-8 Representation
   - UTF-16表現 / UTF-16 Representation
   - ユニコードのスカラ表現 / Unicode Scalar Representation

## [コレクション型 / Collection Types](https://docs.swift.org/swift-book/LanguageGuide/CollectionTypes.html)
 -  コレクション型の変更可否 / Mutability of Collections
 -  配列型 / Arrays
   - 配列型の糖衣構文 / Array Type Shorthand Syntax
   - 空配列の生成 / Creating an Empty Array
   - デフォルト値を持つ配列の生成 / Creating an Array with a Default Value
   - 二つの配列を連結することによる配列の生成 / Creating an Array by Adding Two Arrays Together
   - 配列リテラルによる配列の生成 / Creating an Array with an Array Literal
   - 配列へのアクセスと変更 / Accessing and Modifying an Array
   - 配列のイテレート / Iterating Over an Array
 -  集合型 / Sets
   - 集合型のハッシュ値 / Hash Values for Set Types
   - 集合型の構文 / Set Type Syntax
   - 空集合の生成と初期化 / Creating and Initializing an Empty Set
   - 配列リテラルによる集合の初期化 / Creating a Set with an Array Literal
   - 集合へのアクセスと変更 / Accessing and Modifying a Set
   - 集合のイテレート / Iterating Over a Set
 - 集合演算の実行 / Performing Set Operations
   - 基本的な集合の演算 / Fundamental Set Operations
   - 集合の要素と同一性 / Set Membership and Equality
 -  辞書型 / Dictionaries
   - 辞書型の糖衣構文 / Dictionary Type Shorthand Syntax
   - 空辞書の生成 / Creating an Empty Dictionary
   - 辞書リテラルによる辞書の生成 / Creating a Dictionary with a Dictionary Literal
   - 辞書へのアクセスと変更 / Accessing and Modifying a Dictionary
   - 辞書のイテレート / Iterating Over a Dictionary

## [制御構文 / Control Flow](https://docs.swift.org/swift-book/LanguageGuide/ControlFlow.html)
 -  for-inループ / For-In Loops
 -  whileループ / While Loops
   - while文 / While
   - repeat-while文 / Repeat-While
 -  条件文 / Conditional Statements
   - if文 / If
   - switch文 / Switch
     - 暗黙的なfallthroughはない /  No Implicit Fallthrough
     - 区間によるパターンマッチ / Interval Matching
     - タプル / Tuples
     - バリューバインディングパターン / Value Bindings
     - where / Where
     - ケースの合成 / Compound Cases
 -  フロー制御文 / Control Transfer Statements
   - continue / Continue
   - break / Break
     - ループ文でのbreak / Break in a Loop Statement
     - switch文でのbreak / Break in a Switch Statement
   - fallthrough / Fallthrough
   - label文 / Labeled Statements
 - 早期リターン / Early Exit
 - APIの利用可否をチェックする / Checking API Availability

## [関数 / Functions](https://docs.swift.org/swift-book/LanguageGuide/Functions.html)
 - 関数の定義と呼び出し / Defining and Calling Functions
 - 関数の引数と戻り値 / Function Parameters and Return Values
   - 引数なしの関数 / Functions Without Parameters
   - 複数の引数ありの関数 / Functions With Multiple Parameters
   - 戻り値なしの関数 / Functions Without Return Values
   - 複数の戻り値ありの関数 / Functions with Multiple Return Values
     - オプショナルのタプル型の戻り値 / Optional Tuple Return Types
 - 関数の引数ラベルとパラメータ名 / Function Argument Labels and Parameter Names
   - 引数ラベルの指定 / Specifying Argument Labels
   - 引数ラベルの省略 / Omitting Argument Labels
   - 引数のデフォルト値 / Default Parameter Values
   - 可変長引数 / Variadic Parameters
   - inout引数 / In-Out Parameters
 - 関数型 / Function Types
   - 関数型を利用する / Using Function Types
   - 引数の型としての関数型 / Function Types as Parameter Types
   - 戻り値の型としての関数型 / Function Types as Return Types
 - 関数のネスト / Nested Functions

## [クロージャ / Closures](https://docs.swift.org/swift-book/LanguageGuide/Closures.html)
 -  クロージャ式 / Closure Expressions
   - ソート関数 / The Sorted Method
   - クロージャ式の構文 / Closure Expression Syntax
   - コンテキストからの型推論 / Inferring Type From Context
   - 1つの式を持つクロージャの暗黙的な戻り値 / Implicit Returns from Single-Expression Closures
   - 簡略引数名 / Shorthand Argument Names
   - 演算子関数 / Operator Methods
 - トレイリングクロージャ / Trailing Closures
 - 値のキャプチャ / Capturing Values
 - クロージャは参照型 / Closures Are Reference Types
 - クロージャのエスケープ / Escaping Closures
 - autoclosure属性 / Autoclosures

## [列挙型 / Enumerations](https://docs.swift.org/swift-book/LanguageGuide/Enumerations.html)
 -  列挙型の構文 / Enumeration Syntax
 -  switch文による列挙型の値のパターンマッチ / Matching Enumeration Values with a Switch Statement
 -  列挙型のイテレート / Iterating over Enumeration Cases
 -  連想値 / Associated Values
 -  ローバリュー / Raw Values
   - 暗黙的に代入されるローバリュー / Implicitly Assigned Raw Values
   - ローバリューからの初期化 / Initializing from a Raw Value
 -  再帰的な列挙型 / Recursive Enumerations

## [構造体とクラス / Structures and Classes](https://docs.swift.org/swift-book/LanguageGuide/ClassesAndStructures.html)
 - 構造体とクラスの比較 / Comparing Structures and Classes
   - 定義構文 / Definition Syntax
   - 構造体とクラスのインスタンス / Structure and Class Instances
   - プロパティへの操作 / Accessing Properties
   - 構造体のメンバーワイズイニシャライザ / Memberwise Initializers for Structure Types
 -  構造体と列挙型は値型 / Structures and Enumerations Are Value Types
 -  クラスは参照型 / Classes Are Reference Types
   - アイデンティティ演算子 / Identity Operators
   - ポインタ / Pointers

## [プロパティ / Properties](https://docs.swift.org/swift-book/LanguageGuide/Properties.html)
 - ストアドプロパティ / Stored Properties
   - 構造体インスタンスのストアドプロパティ / Stored Properties of Constant Structure Instances
   - lazyストアドプロパティ / Lazy Stored Properties
   - ストアドプロパティとインスタンス変数 / Stored Properties and Instance Variables
 - コンピューテッドプロパティ / Computed Properties
   - セッター定義での簡略表記 / Shorthand Setter Declaration
   - 読み取り専用コンピューテッドプロパティ / Read-Only Computed Properties
 - プロパティオブザーバー / Property Observers
 - グローバル変数とローカル変数 / Global and Local Variables
 - 型プロパティ / Type Properties
   - 型プロパティの構文 / Type Property Syntax
   - 型プロパティの参照と代入 / Querying and Setting Type Properties

## [メソッド / Methods](https://docs.swift.org/swift-book/LanguageGuide/Methods.html)
 - インスタンスメソッド / Instance Methods
   - selfプロパティ / The self Property
   - インスタンスメソッドからの値型の変更 / Modifying Value Types from Within Instance Methods
   - mutatingメソッドからのselfの代入 / Assigning to self Within a Mutating Method
 - 型メソッド / Type Methods

## [添字 / Subscripts](https://docs.swift.org/swift-book/LanguageGuide/Subscripts.html)
 - 添字の構文 / Subscript Syntax
 - 添字の使い方 / Subscript Usage
 - 添字のオプション / Subscript Options

## [継承 / Inheritance](https://docs.swift.org/swift-book/LanguageGuide/Inheritance.html)
 - 基底クラスの定義 / Defining a Base Class
 - サブクラス化 / Subclassing
 - オーバーライド / Overriding
   - スーパークラスのメソッド、プロパティ、および添字へのアクセス / Accessing Superclass Methods, Properties, and Subscripts
   - メソッドのオーバーライド / Overriding Methods
   - プロパティのオーバーライド / Overriding Properties
     - プロパティのゲッターとセッターのオーバーライド / Overriding Property Getters and Setters
     - プロパティオブザーバーのオーバーライド / Overriding Property Observers
 - オーバーライドの防止 / Preventing Overrides

## [初期化 / Initialization](https://docs.swift.org/swift-book/LanguageGuide/Initialization.html)
 -  ストアドプロパティの初期値の設定 / Setting Initial Values for Stored Properties
   - イニシャライザ / Initializers
   - プロパティのデフォルト値 / Default Property Values
 - イニシャライザのカスタマイズ / Customizing Initialization
   - 初期化パラメータ / Initialization Parameters
   - パラメータ名と引数ラベル / Parameter Names and Argument Labels
   - 引数ラベルなしの初期化パラメータ / Initializer Parameters Without Argument Labels
   - オプショナルのプロパティ型 / Optional Property Types
   - 初期化中の定数プロパティの代入 / Assigning Constant Properties During Initialization
 - デフォルトイニシャライザ / Default Initializers
   - 構造体のメンバーワイズイニシャライザ / Memberwise Initializers for Structure Types
 - 値型の初期化の委譲 / Initializer Delegation for Value Types
 - クラスの継承と初期化 / Class Inheritance and Initialization
   - 指定イニシャライザとコンビニエンスイニシャライザ / Designated Initializers and Convenience Initializers
   - 指定イニシャライザとコンビニエンスイニシャライザの構文 / Syntax for Designated and Convenience Initializers
   - クラス型のイニシャライザの委譲 / Initializer Delegation for Class Types
   - 2段階初期化 / Two-Phase Initialization
   - イニシャライザの継承とオーバーライド / Initializer Inheritance and Overriding
   - 自動的なイニシャライザの継承 / Automatic Initializer Inheritance
   - 指定イニシャライザとコンビニエンスイニシャライザの実装例 / Designated and Convenience Initializers in Action
 - 失敗可能イニシャライザ / Failable Initializers
   - 列挙型の失敗可能イニシャライザ / Failable Initializers for Enumerations
   - ローバリューを持つ列挙型の失敗可能イニシャライザ / Failable Initializers for Enumerations with Raw Values
   - 失敗可能イニシャライザの伝播 / Propagation of Initialization Failure
   - 失敗可能イニシャライザのオーバーライド / Overriding a Failable Initializer
   - init!の失敗可能イニシャライザ / The init! Failable Initializer
 - 必須イニシャライザ / Required Initializers
 - クロージャや関数を用いたプロパティのデフォルト値の設定 / Setting a Default Property Value with a Closure or Function

## [終了処理 / Deinitialization](https://docs.swift.org/swift-book/LanguageGuide/Deinitialization.html)
 - 終了処理はどのように働くか / How Deinitialization Works
 - 終了処理の実装例 / Deinitializers in Action

## [オプショナルチェイニング / Optional Chaining](https://docs.swift.org/swift-book/LanguageGuide/OptionalChaining.html)
 - 強制アンラップの代替としてのオプショナルチェイニング / Optional Chaining as an Alternative to Forced Unwrapping
 - オプショナルチェイニングのためのモデルクラスの定義 / Defining Model Classes for Optional Chaining
 - オプショナルチェイニングを通してプロパティへアクセスする / Accessing Properties Through Optional Chaining
 - オプショナルチェイニングを通してメソッドを実行する / Calling Methods Through Optional Chaining
 - オプショナルチェイニングを通して添字へアクセスする / Accessing Subscripts Through Optional Chaining
   - オプショナル型の添字へのアクセス / Accessing Subscripts of Optional Type
 - オプショナルチェイニングの連鎖 / Linking Multiple Levels of Chaining
 - オプショナル型の戻り値を持つメソッドのオプショナルチェイニング / Chaining on Methods with Optional Return Values

## [エラー処理 / Error Handling](https://docs.swift.org/swift-book/LanguageGuide/ErrorHandling.html)
 - エラーの表現とスロー / Representing and Throwing Errors
 - エラーの処理 / Handling Errors
   - throw関数を用いたエラーの伝播 / Propagating Errors Using Throwing Functions
   - do-catchを用いたエラー処理 / Handling Errors Using Do-Catch
   - エラーをオプショナル値にに変換する / Converting Errors to Optional Values
   - エラーの伝播を無効にする / Disabling Error Propagation
 - スコープを抜けるときのクリーンアップ処理の指定 / Specifying Cleanup Actions

## [型キャスト / Type Casting](https://docs.swift.org/swift-book/LanguageGuide/TypeCasting.html)
 - 型キャストのためのクラス階層の定義 / Defining a Class Hierarchy for Type Casting
 - 型チェック / Checking Type
 - ダウンキャスト / Downcasting
 - Any型とAnyObject型の型キャスト / Type Casting for Any and AnyObject

## [ネストされた型 / Nested Types](https://docs.swift.org/swift-book/LanguageGuide/NestedTypes.html)
 - ネストされた型の実装例 / Nested Types in Action
 - ネストされた型の参照 / Referring to Nested Types

## [エクステンション / Extensions](https://docs.swift.org/swift-book/LanguageGuide/Extensions.html)
 - エクステンションの構文 / Extension Syntax
 - コンピューテッドプロパティ / Computed Properties
 - イニシャライザ / Initializers
 - メソッド / Methods
   - mutatingインスタンスメソッド / Mutating Instance Methods
 - 添字 / Subscripts
 - ネストした型 / Nested Types

## [プロトコル / Protocols](https://docs.swift.org/swift-book/LanguageGuide/Protocols.html)
 - プロトコルの構文 / Protocol Syntax
 - プロトコルの制約 / Property Requirements
 - メソッドの制約 / Method Requirements
 - mutatingメソッドの制約 / Mutating Method Requirements
 - イニシャライザの制約 / Initializer Requirements
   - プロトコルのイニシャライザ制約のクラス実装 / Class Implementations of Protocol Initializer Requirements
   - 失敗可能イニシャライザの制約 / Failable Initializer Requirements
 - プロトコルを型として扱う / Protocols as Types
 - デリゲートデザインパターン / Delegation
 - エクステンションによるプロトコルへの準拠 / Adding Protocol Conformance with an Extension
   - 条件付きプロトコル準拠 / Conditionally Conforming to a Protocol
   - エクステンションによるプロトコル準拠の宣言 / Declaring Protocol Adoption with an Extension
 - プロトコル型のコレクション / Collections of Protocol Types
 - プロトコル継承 / Protocol Inheritance
 - クラス専用プロトコル / Class-Only Protocols
 - プロトコルコンポジション / Protocol Composition
 - プロトコル準拠のチェック / Checking for Protocol Conformance
 - オプショナルなプロトコル制約 / Optional Protocol Requirements
 - プロトコルエクステンション / Protocol Extensions
   - デフォルト実装を与える / Providing Default Implementations
   - プロトコルエクステンションに条件を付与する / Adding Constraints to Protocol Extensions

## [ジェネリクス / Generics](https://docs.swift.org/swift-book/LanguageGuide/Generics.html)
 - ジェネリクスが解決する問題 / The Problem That Generics Solve
 - ジェネリック関数 / Generic Functions
 - 型パラメータ / Type Parameters
 - 型パラメータの命名 / Naming Type Parameters
 - ジェネリック型 / Generic Types
 - ジェネリック型の拡張 / Extending a Generic Type
 - 型制約 / Type Constraints
   - 型制約の構文 / Type Constraint Syntax
   - 型制約の実装例 / Type Constraints in Action
 - 連想型 / Associated Types
   - 連想型の実装例 / Associated Types in Action
   - 既存の型を連想型を指定することにより拡張する / Extending an Existing Type to Specify an Associated Type
   - 連想型に制約を追加する / Adding Constraints to an Associated Type
   - 連想型の制約に自身のプロトコルを利用する / Using a Protocol in Its Associated Type’s Constraints
 - ジェネリックなwhere句 / Generic Where Clauses
 - ジェネリックなwhere句を利用したエクステンション / Extensions with a Generic Where Clause
 - ジェネリックなwhere句を利用した連想型 / Associated Types with a Generic Where Clause
 - ジェネリックな添字 / Generic Subscripts

## [自動参照カウント / Automatic Reference Counting](https://docs.swift.org/swift-book/LanguageGuide/AutomaticReferenceCounting.html)
 - ARCはどのように働くか / How ARC Works
 - ARCの実装例 / ARC in Action
 - クラスインスタンス間の循環強参照 / Strong Reference Cycles Between Class Instances
 - クラスインスタンス間の循環強参照を解決する / Resolving Strong Reference Cycles Between Class Instances
   - 弱参照 / Weak References
   - unowend参照 / Unowned References
   - unowend参照とIUOプロパティ / Unowned References and Implicitly Unwrapped Optional Properties
 - クロージャの循環強参照 / Strong Reference Cycles for Closures
 - クロージャの循環強参照を解決する / Resolving Strong Reference Cycles for Closures
   - キャプチャリストの定義 / Defining a Capture List
   - 弱参照とunowend参照 / Weak and Unowned References

## [メモリ安全 / Memory Safety](https://docs.swift.org/swift-book/LanguageGuide/MemorySafety.html)
 - メモリアクセスの参照コンフリクトを理解する / Understanding Conflicting Access to Memory
   - メモリアクセスの特徴 / Characteristics of Memory Access
 - inoutパラメータの参照コンフリクト / Conflicting Access to In-Out Parameters
 - メソッドでのselfへの参照コンフリクト / Conflicting Access to self in Methods
 - プロパティへの参照コンフリクト / Conflicting Access to Properties

## [アクセス制御 / Access Control](https://docs.swift.org/swift-book/LanguageGuide/AccessControl.html)
 - モジュールとソースファイル / Modules and Source Files
 - アクセスレベル / Access Levels
   - アクセスレベルの原則 / Guiding Principle of Access Levels
   - デフォルトのアクセスレベル / Default Access Levels
   - 1つのターゲットを持つアプリのためのアクセスレベル / Access Levels for Single-Target Apps
   - フレームワークのためのアクセスレベル / Access Levels for Frameworks
   - ユニットテストターゲットのためのアクセスレベル / Access Levels for Unit Test Targets
 - アクセス制御構文 / Access Control Syntax
 - 独自型を定義したときのアクセスレベル / Custom Types
   - タプル型 / Tuple Types
   - 関数型 / Function Types
   - 列挙型 / Enumeration Types
   - ネストした型 / Nested Types
 - サブクラス化 / Subclassing
 - 定数、変数、プロパティ、soeji / Constants, Variables, Properties, and Subscripts
   - ゲッターとセッター / Getters and Setters
 - イニシャライザ / Initializers
   - デフォルトイニシャライザ / Default Initializers
   - 構造体のデフォルトのメンバーワイズイニシャライザ / Default Memberwise Initializers for Structure Types
 - プロトコル / Protocols
   - プロトコル継承 / Protocol Inheritance
   - プロトコル準拠 / Protocol Conformance
 - エクステンション / Extensions
   - エクステンション内のプライベート変数 / Private Members in Extensions
 - ジェネリクス / Generics
 - 型エイリアス / Type Aliases

## [応用的な演算子 / Advanced Operators](https://docs.swift.org/swift-book/LanguageGuide/AdvancedOperators.html)
 - ビット演算子 / Bitwise Operators
   - ビットNOT演算子 / Bitwise NOT Operator
   - ビットAND演算子 /Bitwise AND Operator
   - ビットOR演算子 /Bitwise OR Operator
   - ビットXOR演算子 /Bitwise XOR Operator
   - ビットシフト演算子 / Bitwise Left and Right Shift Operators
     - 符号なし整数型のシフト演算の動作 / Shifting Behavior for Unsigned Integers
     - 符号あり整数型のシフト演算の動作 / Shifting Behavior for Signed Integers
 - オーバーフロー演算子 / Overflow Operators
   - 値のオーバーフロー / Value Overflow
 -  優先順位と結合性 / Precedence and Associativity
 - 演算子メソッド / Operator Methods
   - 前置演算子と後置演算子 / Prefix and Postfix Operators
   - 複合代入演算子 / Compound Assignment Operators
   - 等価演算子 / Equivalence Operators
 - カスタム演算子 / Custom Operators
   - カスタム中置演算子の優先順位 / Precedence for Custom Infix Operators
