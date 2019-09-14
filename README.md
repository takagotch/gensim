### gensim
---
https://github.com/RaRe-Technologies/gensim


```py
// gensim/test/test_aggregation.py
import logging
import unittest

from gensim.topic_coherence import agregation

class TestAggregation(unittest.TestCase):
  def setUp(self):
    self.confirmed_measures = [1.1, 2.2, 3.3, 4.4]
 
    def testArithmeticMean(self):
      """ """
      obtained = aggregation.arithmetic_mean(self.confirmed_measures)
      expected = 2.75
      self.assertEqual(obtained, expected)

if __name__ == '__main__':
  logging.root.setLevel(logging.WARNING)
  unittest.main()

```

```
```

```
```

