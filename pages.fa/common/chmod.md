# chmod

> تغییر مجوز(ها)ی دسترسی به یک فایل یا پوشه.
> اطلاعات بیشتر: <https://www.gnu.org/software/coreutils/manual/html_node/chmod-invocation.html>.

- به مالک فایل دسترسی اجرا میدهد:

`chmod u+x {{path/to/file}}`

- به کابر مالک دسترسی خواندن|نوشتن یک فایل|پوشه را میدهد:

`chmod u+rw {{path/to/file_or_directory}}`

- دسترسی اجرا را از گروه سلب میکند:

`chmod g-x {{path/to/file}}`

- به تمامی کاربرها دسترسی خواندن و اجرا میدهد:

`chmod a+rx {{path/to/file}}`

- به دیگران(کاربرانی که صاحب فایل نیستند) دسترسی های گروه را میدهد:

`chmod o=g {{path/to/file}}`

- به همگان همه دسترسی(ها) را میدهد:

`chmod o= {{path/to/file}}`

- به صورت بازگشتی به گروه و دیگران دسترسی نوشتن میدهد:

`chmod {{[-R|--recursive]}} g+w,o+w {{path/to/directory}}`

- به صورت بازگشتی در پوشه و زیرپوشه(ها) دسترسی اجرا و خواندن فایل(ها) را میدهد:

`chmod {{[-R|--recursive]}} a+rX {{path/to/directory}}`
