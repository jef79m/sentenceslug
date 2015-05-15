# sentenceslug
a module to generate realtively easy to remember slugs

## Usage

```python
from sentenceslug import SentenceSlug

plainslug = SentenceSlug()

print plainslug.slug
# ManageTheSingleGoal

intslug = SentenceSlug(withint=True)
print intslug.slug
# StateHisEconomicColor926


from sentenceslug import SimpleSlug

plainslug = SimpleSlug()

print plainslug.slug
# HighContract

plainslug = SimpleSlug(withint=True)

print plainslug.slug
#GoodBody134

```