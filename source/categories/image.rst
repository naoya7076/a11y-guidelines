.. _category-image:

画像
------------------------

これらのガイドラインは、画像に関するものです。なお、すべてのガイドラインが[MUST]です。

.. _image-text-alternative:

テキスト情報の提供
~~~~~~~~~~~~~~~~~~

参考: :ref:`exp-image-text-alternative`

.. _gl-image-description:

-  [MUST] 画像に関する過不足のない説明をテキストで提供する。

   .. raw:: html

      <details>

   意図
      *  視覚障害者が画像の存在を認知し、内容を理解できるようにする。
   チェック内容
      *  画像に関する簡潔で過不足ない説明がalt属性やaria-label属性で付加されている。かつ
      *  短いテキストでは充分に説明できない場合には、aria-describedby属性を使うなどして、詳細な説明が提供されている。
   チェック対象
      |markup|
   対応するWCAG 2.1の達成基準
      *  SC 1.1.1:

         *  |SC 1.1.1|
         *  |SC 1.1.1ja|

   .. raw:: html

      </details>

   .. _gl-image-decorative:
-  [MUST] 純粋な装飾目的の画像は、スクリーン・リーダーなどの支援技術が無視するようにする。

   .. raw:: html

      <details>

   意図
      *  不要な情報が提示されないようにすることで、視覚障害者などの情報取得をスムースにする。
   チェック内容
      *  情報や機能性を一切持たない画像は、スクリーン・リーダーで読み上げさせたとき、画像の存在が分からないようになっている。 (空の ``alt`` 属性、 ``role="img"`` などの使用)
   チェック対象
      |markup|
   対応するWCAG 2.1の達成基準
      *  SC 1.1.1:

         *  |SC 1.1.1|
         *  |SC 1.1.1ja|

   .. raw:: html

      </details>

.. _image-visual:

表示と視覚的要素
~~~~~~~~~~~~~~~~

参考: :ref:`exp-image-visual`

.. _gl-image-color-only:

-  [MUST] 特定の色に何らかの意味を持たせている場合、形状、模様など他の視覚的な要素も併せて用い、色が判別できなくてもその意味を理解できるようにする。

   .. raw:: html

      <details>

   意図
      *  視覚障害者や色弱者が、コンテンツを利用できるようにする。
   チェック内容
      *  グレースケール表示でも意図が伝わるようになっている。
   チェック対象
      |visual|
   参考
      *  :ref:`exp-color-only`
      *  :ref:`exp-grayscale`
   対応するWCAG 2.1の達成基準
      *  SC 1.4.1:

         *  |SC 1.4.1|
         *  |SC 1.4.1ja|

   .. raw:: html

      </details>

   .. _gl-image-adjacent-contrast:
-  [MUST] 画像の隣接領域の色とのコントラストを3:1以上にする。

   .. raw:: html

      <details>

   意図
      *  ロービジョン者が、コンテンツを利用できるようにする。
   チェック内容
      *  画像の隣接領域の色とのコントラストが3:1以上になっている。
   チェック対象
      |visual|
   参考
      *  :ref:`exp-contrast`
      *  :ref:`exp-check-contrast`
   対応するWCAG 2.1の達成基準
      *  SC 1.4.11:

         *  |SC 1.4.11|
         *  |SC 1.4.11ja|

   .. raw:: html

      </details>

   .. _gl-image-text-contrast:
-  [MUST] 画像内のテキストや、重要な情報を伝える視覚的要素の色と背景の色に、十分なコントラストを確保する。

   -  テキストの文字サイズが22ポイント以上の場合: 3:1以上 ([SHOULD] 4.5:1以上)
   -  テキストの文字サイズが18ポイント以上で太字の場合: 3:1以上 ([SHOULD] 4.5:1以上)
   -  その他の場合: 4.5:1以上 ([SHOULD] 7:1以上)

   .. raw:: html

      <details>

   意図
      *  ロービジョン者が、コンテンツを利用できるようにする。
   チェック内容
      *  画像内のテキストや、重要な情報を伝える視覚的要素の色と背景の色に、十分なコントラストが確保されている。
   チェック対象
      |visual|
   参考
      *  :ref:`exp-contrast`
      *  :ref:`exp-check-contrast`
   対応するWCAG 2.1の達成基準
      *  SC 1.4.3:

         *  |SC 1.4.3|
         *  |SC 1.4.3ja|

      *  SC 1.4.6:

         *  |SC 1.4.6|
         *  |SC 1.4.6ja|

   .. raw:: html

      </details>

