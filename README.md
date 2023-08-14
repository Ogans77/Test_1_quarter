**Итоговая контрольная работа по основному блоку**

*Задача алгоритмически не самая сложная, однако для полноценного выполнения проверочной работы необходимо:*

1. Создать репозиторий на GitHub
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)

**Задача:**

Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

*Примеры:*

[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]

[“1234”, “1567”, “-2”, “computer science”] → [“-2”]

[“Russia”, “Denmark”, “Kazan”] → []


**Составим блок-схему программы**

![картинка](https://fs3.fotoload.ru/f/0620/1591212881/4da141d5cf.jpg)

Ссылка на блок-схему на [Flowchart](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=%D0%9C%D0%B0%D1%81%D1%81%D0%B8%D0%B2%20%D1%81%20%D1%83%D0%BC%D0%B5%D0%BD%D1%8C%D1%88%D0%B5%D0%BD%D0%B8%D0%B5%D0%BC.drawio#R5VpZc%2BI4EP41PCblUzaPAXLUFrubqdTOsS9bsi2MZ4XFChFIfv3KloRlJAgZriGTpBy5dVjq7q8vu%2BP3J8t7Cqfj30mGcMdzsmXHH3Q8L44Cfq0IL4IQRLEg5LTIBMltCE%2FFK5JER1LnRYZmrYGMEMyKaZuYkrJEKWvRIKVk0R42Irj91CnMkUF4SiE2qV%2BKjI3lsbyooT%2BgIh%2BrJ7ugK3omUA2WJ5mNYUYWGsm%2F7fh9SggTrcmyj3DFO8UXMe9uQ%2B9qYxSVbJcJn6eD8Z9Dgtw%2Be334%2BnCf4zK68sUqzxDP5YHlZtmL4gDKOEPkLaFsTHJSQnzbUHuUzMsMVY9x%2BF0zZkjIlBNdTvyOGHuR0oVzRjhpzCZY9ppHkaebkTlN0Zb9y3HVHrWJkgH3iEwQoy98AEUYsuK5LVQodSNfjVtNfSQF34rnSDV2g%2FA6FJOkHsdOew0GaY6YnNZIgTe0fTSkWjbvkJNryOmJP5GZwsKYI6MSymJcMPQ0hTX7FhybbZaPCoz7BBNaz%2FMziOJRyukzRsm%2FSOsBaYyS0TYhPSPK0HIr%2B1WvE62xUcF80WArAoI01mAVOJsl1mL1Fr4uvgyiT0P66fHzc4rHi2759P2fK%2B%2FC9V9aV6F9W855cJzsyvVtu9a5zlnXra89cb2tr3ygUzfuNGKvw5kW9%2Bt2pNHFRKfuFe1QjV%2B1%2B2rBm%2FaC%2FBrXEyM1mLddbSm1uAcw53MvobyVs1p2AE4qcJXJrPpXzxlYHty0B9q6autyW33tDK66is21NtF%2B5LrKclczrZpcoyDGCJOcwgkfOEW04BJEdL3vsel423AskfLTFkMyilOUWg1JEodB6BzGkAB%2FgznW7IgLXNOQrJvtH1Fp4HyG%2Fa9%2FLZbwt7xw%2FqPB34%2F9n8qRrqH8TcuyzWLolsV6cO9EhmTbJjWuC7ddVHiq7h0LYsWQUh%2ByJqm2HN7pSUMUZ4ENALGX%2BAAcypN2r701V2rBAOgqnOggCI8FAteUx4WjwOJfrScHJ0KBne2m8fnGcyYb54cw4flZi1sQF3nJ2ylnTu0AKi0seAZ0IzsmRZYJwaBZ8QqTer1KNNMq2q0PE%2FY64WDFeUONV%2BmZnNxZJUW6TLao1EYcXDnXjgNACwhSZj8a8rdXURPIaDRD%2B4b2dgMKflXQCAN2Lt9hBqG111CxFRbBHZcCLcr8hlL4cj1EZc5Nq%2BEuxmSSzGfvdhWj0cizx0oZSEB4IFehrL3Uaz%2F0zFApjk0vAY7lJcKPpu%2BudxGxkpnrcoXv1X8XF%2F%2F4kdvSai8KVKSjlxIswY8fHkmtLUntxaj1Zm3dobYQnDP2sRRwTlpKOEGyf4HJvSUCNDRw9%2BTeAxaXpdzTSVyW%2B%2BHADXYEt3sqn2Xnuxkr%2FEGsnL%2B8xGaD2WwSGy9STm7ftxftCUdMZZxfACZ2aZ61ALCKnz5gAUB7V7qpABB67QKACgr2rACoZY6PG7MCoGWdFW9lRTMcrFLQ9US1muX4hsiPnpru5el9d93V%2B6FruvquzdV7m8W5H5YuuZK%2FxTbtkp6e19ebKCjPmZ%2FupdlhtFZ1Abb8FFhedR8tP%2FU%2BXAyrDvCTB7Fqm7pio0VHlRaFfS%2BFfb9EVQ%2F8lqpbszXvlNmaF384TQ93NeHRWTXdTNemtI6p2h8s7K7%2BqtiRkXQ%2Bqdn2FgYSIbZhsimyCavfik5KptHFjw0soP45DFjioIWVAFi%2BW7Bh5WjfLagPGTWR3RVlMTPfchz907K9GOupwHH1nanJ2bh7ECPEb5uvNkUK0Hz66t%2F%2BDw%3D%3D)
