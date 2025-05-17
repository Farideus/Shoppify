// Список товаров
const products = [
  {
    id: 1,
    name: 'Футболка',
    price: 1000,
    image: 'https://via.placeholder.com/150/90ee90/000000?text=Футболка',
    category: 'Одежда'
  },
  {
    id: 2,
    name: 'Ноутбук',
    price: 50000,
    image: 'https://via.placeholder.com/150/ffffa0/000000?text=Ноутбук',
    category: 'Электроника'
  },
  {
    id: 3,
    name: 'Кроссовки',
    price: 3000,
    image: 'https://via.placeholder.com/150/90ee90/000000?text=Кроссовки',
    category: 'Одежда'
  },
  {
    id: 4,
    name: 'Телефон',
    price: 25000,
    image: 'https://via.placeholder.com/150/ffffa0/000000?text=Телефон',
    category: 'Электроника'
  }
];

let cart = [];

// Отображение всех товаров
function renderProducts() {
  const productList = document.getElementById('product-list');
  productList.innerHTML = '';
  products.forEach(p => {
    const div = document.createElement('div');
    div.className = 'product';
    div.innerHTML = `
      <img src="${p.image}" alt="${p.name}" />
      <h3>${p.name}</h3>
      <p>${p.price} ₽</p>
      <p><em>${p.category}</em></p>
      <button onclick="addToCart(${p.id})">Добавить в корзину</button>
    `;
    productList.appendChild(div);
  });
}

// Добавление товара в корзину
function addToCart(id) {
  const product = products.find(p => p.id === id);
  cart.push(product);
  updateCartCount();
}

// Обновление количества в корзине
function updateCartCount() {
  document.getElementById('cart-count').textContent = cart.length;
}

// Отображение корзины
function showCart() {
  const cartSection = document.getElementById('cart-section');
  const itemsList = document.getElementById('cart-items');
  const totalPrice = document.getElementById('total-price');
  const paymentDiv = document.getElementById('payment-options');

  itemsList.innerHTML = '';
  let total = 0;

  cart.forEach(p => {
    const li = document.createElement('li');
    li.textContent = `${p.name} - ${p.price} ₽`;
    itemsList.appendChild(li);
    total += p.price;
  });

  totalPrice.textContent = total;
  paymentDiv.classList.remove('hidden');
  cartSection.classList.remove('hidden');
}

// Оформление заказа (заглушка)
function checkout() {
  const selected = document.querySelector('input[name="payment"]:checked');
  if (!selected) {
    alert('Выберите способ оплаты!');
    return;
  }

  alert(`Спасибо за заказ!\nСпособ оплаты: ${selected.value}\nКоличество товаров: ${cart.length}`);
  
  cart = [];
  updateCartCount();
  showCart();
}

// Инициализация при загрузке
renderProducts();
