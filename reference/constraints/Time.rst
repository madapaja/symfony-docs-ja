.. 2011/07/23 yanchi 36a165e88363fd6e5b5eb0ae712303dd362545be

Time
====

値が「HH:MM:SS」形式による有効な時間文字列であることを検証します。

.. code-block:: yaml

    properties:
        createdAt:
            - DateTime: ~

オプション
----------

* ``message``: 検証に失敗した場合のエラーメッセージ
