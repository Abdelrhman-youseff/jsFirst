// let test: number = 1;
// console.log("here");
// let bar: string |  number = 3;
interface Product {
    id: number;
    name: string;
    price: number;
    
}

interface Store {
    products: Product[];
    addProduct: (product: Product) => void;
    
}

class ProductStore implements Store {
    products: Product[] = [];

    addProduct(product: Product) {
        this.products.push(product);
    }   
}

const store = new ProductStore();

const product1: Product = { id: 1, name: 'Mouse', price: 999.99};
const product2: Product = { id: 2, name: 'Keyboard', price: 19.99};

store.addProduct(product1);
store.addProduct(product2);


