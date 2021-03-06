.. _category-multimedia:

音声・映像映像
------------------------------------------------

これらのガイドラインは、音声のみのコンテンツ、音声を含む動画コンテンツ、映像のみの動画コンテンツに関するものです。

.. _multimedia-perceivable:

存在を認知できる
~~~~~~~~~~~~~~~~

.. _gl-multimedia-perceivable:

-  [MUST] 音声・映像コンテンツの存在を認知できるようにする。

   .. raw:: html

      <details>

   意図
      *  視覚障害者、聴覚障害者が音声や映像を含むコンテンツの存在を認知できるようにする。
   チェック内容
      *  ページ内に埋め込まれる音声/動画プレイヤーについて、適切なラベル付けがされていてそこにプレイヤーがあることが容易に認知できるようになっている。または
      *  前後のテキストから、そこにプレイヤーがあることが推測できる。
   チェック対象
      |visual| 、 |markup|
   参考
      *  :ref:`exp-multimedia-perceivable`
   対応するWCAG 2.1の達成基準
      *  SC 1.1.1:

         *  |SC 1.1.1|
         *  |SC 1.1.1ja|

   .. raw:: html

      </details>

.. _multimedia-operable:

操作を阻害しない
~~~~~~~~~~~~~~~~

.. _gl-multimedia-operable:

-  [MUST] 3秒以上の長さの音声を自動再生しない。

   .. raw:: html

      <details>

   意図
      *  スクリーン・リーダーの音声出力を阻害しない。
   チェック内容
      *  自動再生される音声はない。または
      *  自動再生される音声は3秒以内の長さになっている。
   チェック対象
      |visual|
   参考
      *  :ref:`exp-multimedia-autoplay`
   対応するWCAG 2.1の達成基準
      *  SC 1.4.2:

         *  |SC 1.4.2|
         *  |SC 1.4.2ja|

   .. raw:: html

      </details>

   .. _gl-multimedia-no-trap:
-  [MUST] 音声/動画のプレイヤーをページに埋め込む場合、そのコンポーネントにフォーカスした状態から、Tabキー、矢印キー、Escキーなどで抜け出すことができるようにする。

   .. raw:: html

      <details>

   意図
      *  キーボードのみを利用している場合に、ページ中の特定のコンポーネントがページの他の部分へのアクセスを阻害しないようにする。
   チェック内容
      *  音声/動画プレイヤーにフォーカスがある状態で、Tab/Shift+Tabキー、矢印キー、Escキーのいずれかの操作で、フォーカスをプレイヤーから外すことができる。
   チェック対象
      |behavior|
   参考
      *  :ref:`exp-keyboard-notrap`
   対応するWCAG 2.1の達成基準
      *  SC 2.1.2:

         *  |SC 2.1.2|
         *  |SC 2.1.2ja|

   .. raw:: html

      </details>


.. _multimedia-content-access:

内容へのアクセス 
~~~~~~~~~~~~~~~~

参考: :ref:`exp-multimedia-content-access`

.. _gl-multimedia-text-alternative:

-  [MUST] テキスト情報の代替情報として音声・映像コンテンツを用い、そのコンテンツがテキスト情報の代替であることを明示する。

   .. raw:: html

      <details>

   意図
      *  音声・映像コンテンツの利用ができないユーザーも支障なくコンテンツを利用できるようにする。
   チェック内容
      *  音声・映像コンテンツは、そのコンテンツがなくても不足なく情報が伝わるような内容で、そのコンテンツがテキスト情報の代替もしくは補助的な位置づけであることが明示されている。
   チェック対象
      |visual|
   対応するWCAG 2.1の達成基準
      *  SC 1.2.1:

         *  |SC 1.2.1|
         *  |SC 1.2.1ja|

      *  SC 1.2.2:

         *  |SC 1.2.2|
         *  |SC 1.2.2ja|

      *  SC 1.2.3:

         *  |SC 1.2.3|
         *  |SC 1.2.3ja|

      *  SC 1.2.4:

         *  |SC 1.2.4|
         *  |SC 1.2.4ja|

   .. raw:: html

      </details>

   .. _gl-multimedia-caption:
-  [MUST] テキストの代替情報ではない音声・映像コンテンツにおいて、音声情報には、同期したキャプションを提供する。

   ただしライブ配信の場合は [SHOULD]

   .. raw:: html

      <details>

   意図
      *  音声情報を理解できなくてもサービスの利用が困難にならないようにする。
      *  聴覚紹介者が、音声コンテンツおよび動画コンテンツ内の音声を理解できるようにする。
   チェック内容
      *  音声を含むコンテンツには、同期したキャプションが提供されている。
   チェック対象
      |visual|
   対応するWCAG 2.1の達成基準
      *  SC 1.2.2:

         *  |SC 1.2.2|
         *  |SC 1.2.2ja|

      *  SC 1.2.4:

         *  |SC 1.2.4|
         *  |SC 1.2.4ja|

   .. raw:: html

      </details>

   .. _gl-multimedia-video-description:
-  [MUST] テキストの代替情報ではない音声・映像コンテンツにおいて、映像がある収録済みコンテンツの場合、映像の内容が分かるような同期した音声情報、またはテキストによる説明を提供する。

   .. raw:: html

      <details>

   意図
      *  映像情報を理解できなくてもサービスの利用が困難にならないようにする。
      *  視覚障害者が、映像コンテンツを理解できるようにする。
   チェック内容
      *  動画は、元々収録されている音声トラックの内容から容易に映像を推測できる。または
      *  動画には音声解説が含まれている。または
      *  映像に関するテキストによる説明が提供されている。
   チェック対象
      |visual|
   対応するWCAG 2.1の達成基準
      *  SC 1.2.3:

         *  |SC 1.2.3|
         *  |SC 1.2.3ja|

   .. raw:: html

      </details>

   .. _gl-multimedia-transcript:
-  [MUST] テキストの代替情報ではない音声・映像コンテンツにおいて、映像がなく音声のみの収録済みコンテンツの場合は、書き起こしテキストを提供する。

   .. raw:: html

      <details>

   意図
      *  音声コンテンツを理解できなくてもサービスの利用が困難にならないようにする。
      *  聴覚障害者が音声のみのコンテンツを理解できるようにする。
   チェック内容
      *  映像がない音声のみのコンテンツについて、音声を書き起こしたテキストが提供されている。
   チェック対象
      |visual|
   対応するWCAG 2.1の達成基準
      *  SC 1.2.1:

         *  |SC 1.2.1|
         *  |SC 1.2.1ja|

   .. raw:: html

      </details>

   .. _gl-multimedia-sign-language:
-  [SHOULD] 収録済みコンテンツの音声情報には、同期した手話通訳を提供する。

   .. raw:: html

      <details>

   意図
      *  手話を主たる言語として使う聴覚障害者が、音声コンテンツまたは動画コンテンツ中の音声を理解できるようにする。
   チェック内容
      *  動画の音声情報には同期した手話通訳が提供されている。
   チェック対象
      |visual|
   対応するWCAG 2.1の達成基準
      *  SC 1.2.6:

         *  |SC 1.2.6|
         *  |SC 1.2.6ja|

   .. raw:: html

      </details>

   .. _gl-multimedia-background-sound:
-  [SHOULD] 映像がなく音声のみの収録済みコンテンツの場合で主たる発話音声があるとき、背景音がない、もしくは主たる発話音声に対して背景音の音量が少なくとも20db小さい状態にする。

   .. raw:: html

      <details>

   意図
      *  音声コンテンツの内容を聞き取りやすいものにする。
   チェック内容
      *  .. todo:: SC 1.4.7のチェック方法を検討
   チェック対象
      |visual|
   対応するWCAG 2.1の達成基準
      *  SC 1.4.7:

         *  |SC 1.4.7|
         *  |SC 1.4.7ja|

   .. raw:: html

      </details>
