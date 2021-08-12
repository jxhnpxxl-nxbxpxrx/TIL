# Eloquent ORM

## Eloquent we mostly see on Repository files
```sh
->select()            # select db value
->where()             # make conditions
->orderBy()           # order by selected table row
->get()               # wants to get a number of records an return Collection
->first()             # wants to only get the first row of the collection
->all()               # yield all the records of a table.
->find()              # find the matching record by the parameter use
->save()              # save selected the record
->delete()            # deletes only selected record
->destroy()           # deletes 1 or more selected record
->pluck()             # extracts certain value
->value()             # sele ct specific value
```


## Eloquent we mostly see on Model files

```sh
->hasOne()            # one to one relationships
->belongsTo()         # this relates to ->hasOne() or ->hasMany()
->hasMany()           # one to many relationships
->withDefault()       # this returns a default value when the data is empty collection
```


## Eloquent we mostly see on Migration files

```sh
->string()                # set value as string
->integer()               # set value to -2^31 (-2,147,483,648) to 2^31-1 (2,147,483,647)
->increments()            # set value to auto increments
->timestamp()             # creates row for created_at and updated_at
->date()                  # set value to date format
->boolean()               # set value to only boolean (1 or 0)
->smallInteger()          # set value to small whole numbers that range from –32,767 to 32,76
->decimal()               # set value to total number of digits is specified in size
->text()                  # set value to maximum length of 65,535
->longText()              # set value to maximum length of 4,294,967,295
->tinyText()              # set value to maximum length of 255
->dropIfExists()          # drop table if exists
```






