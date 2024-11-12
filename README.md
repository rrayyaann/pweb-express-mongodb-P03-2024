# pweb-express-mongodb-P03-2024

**KELOMPOK P03**
| Nama                       | NRP |
|----------------------------|------------|
|Muhamad Arrayyan            | 5027231014 |
|Salomo                      | 5027221063 |
|Malvin Putra Rismahardian	 | 5027231048 |


# Alur Development (Development Flow)

Flow:
Bikin Schema di model -> Controller -> Route

# Alur Aplikasi (Application Flow)

## API Endpoints

### Products

1. Get All Products

   ```
   GET /products

   Flow:
   Client Request → Routes → Controller → Model → Database
   ```

2. Get Product by ID

   ```
   GET /products/:id

   Flow:
   Client Request → Routes → Controller → Model → Database
   ```

3. Create Product

   ```
   POST /products

   Flow:
   Client Request → Routes → Controller → Model → Database
   ```

4. Update Product

   ```
   PUT /products/:id

   Flow:
   Client Request → Routes → Controller → Model → Database
   ```

5. Delete Product

   ```
   DELETE /products/:id

   Flow:
   Client Request → Routes → Controller → Service → Model → Database
   ```
