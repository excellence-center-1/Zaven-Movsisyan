Python
------
| Task 7 | Resizable table |
---------
Իրականացնել Table դասը, որը պահում է ամբողջ թվեր երկչափ աղյուսակում։ Table(rows,
cols) սկզբնարժեքավորման ժամանակ նմուշին փոխանցվում են աղյուսակի տողերի և սյուների քանակները։
Տողերը և սյուները համարակալվում են զրոյից սկսած։
table.get_value(row, col) — կարդալ արժեքը row տողի, col սյան վանդակից։ Եթե row և col ինդեքսներով վանդակը ընկած չէ աղյուսակի ներսում, ապա պետք է վերադարձնել None։
table.set_value(row, col, value) — գրել թիվը row տողի, col սյան վանդակում։ Երաշխավորվում է, որ թեստերում գրառումը կկատարվի միայն աղյուսակի ներսի վանդակներում։
table.n_rows() — վերադարձնել աղյուսակում տողերի քանակը
table.n_cols() — վերադարձնել աղյուսակում սյուների քանակը
table.delete_row(row) — հեռացնել row համարով տողը
table.delete_col(row) — հեռացնել col համարով սյունը
table.add_row(row) — աղյուսակին ավելացնել row ինդեքսով նոր տող։ Տողերի քանակը պետք է մեծանա
մեկով։ Նոր տողը բաղկացած է զրոներից։
table.add_col(col) — աղյուսակին ավելացնել col ինդեքսով նոր սյուն։ Սյուների քանակը պետք է մեծանան
մեկով։ Նոր սյունը բաղկացած է զրոներից։

----------------
Input format
-----------------



Յուրաքանչյուր թեստ իրենից ներկայացնում է կոդ, որում կօգտագործվի ձեր դասը։
Լուծումը պարունակող ֆայլը պարտադիր չէ անվանել solution.py, այն կվերանվանվի ավտոմատ կերպով։
Թեստը աշխատեցվում է ձեր դասով, իսկ նրա արտածումը համեմատվում է ճիշտ պատասխանի հետ։
