import React, { useState, useEffect, useMemo } from 'react';
import { 
  ShoppingBag, Heart, Search, User, X, ChevronRight, ChevronLeft, 
  Star, SlidersHorizontal, Check, Plus, Minus, ArrowRight, ShieldCheck, 
  Truck, RefreshCw, Eye, Sparkles, Filter, Lock, Tag, MapPin, CreditCard, Menu
} from 'lucide-react';

const INITIAL_PRODUCTS = [
  {
    id: 'prod-1',
    name: 'Satin Wrap Midi Dress',
    category: 'Women',
    price: 245,
    originalPrice: 290,
    rating: 4.8,
    reviewsCount: 42,
    badge: 'Bestseller',
    colors: [
      { name: 'Champagne', hex: '#E6D7C3' },
      { name: 'Midnight Black', hex: '#1A1A1A' },
      { name: 'Emerald', hex: '#1B4D3E' }
    ],
    sizes: ['XS', 'S', 'M', 'L'],
    images: [
      'https://images.unsplash.com/photo-1595777457583-95e059d581b8?auto=format&fit=crop&w=800&q=80',
      'https://images.unsplash.com/photo-1572804013309-59a88b7e92f1?auto=format&fit=crop&w=800&q=80'
    ],
    description: 'Crafted from fluid silk-satin, this wrap dress features a flattering v-neckline, subtly puffed sleeves, and a tailored belted waistline. Perfect for evening galas and summer cocktail gatherings.',
    isNew: false
  },
  {
    id: 'prod-2',
    name: 'Tailored Wool Double-Breasted Coat',
    category: 'Women',
    price: 480,
    originalPrice: null,
    rating: 4.9,
    reviewsCount: 28,
    badge: 'New',
    colors: [
      { name: 'Camel', hex: '#C19A6B' },
      { name: 'Charcoal', hex: '#333333' }
    ],
    sizes: ['S', 'M', 'L', 'XL'],
    images: [
      'https://images.unsplash.com/photo-1539533018447-63fcce2678e3?auto=format&fit=crop&w=800&q=80',
      'https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?auto=format&fit=crop&w=800&q=80'
    ],
    description: 'A timeless silhouette engineered in heavyweight Italian wool blend. Structured shoulders and gold-embossed horn buttons elevate this indispensable autumn essential.',
    isNew: true
  },
  {
    id: 'prod-3',
    name: 'Italian Calfskin Leather Trench Blazer',
    category: 'Men',
    price: 650,
    originalPrice: 720,
    rating: 5.0,
    reviewsCount: 15,
    badge: 'Sale',
    colors: [
      { name: 'Espresso', hex: '#3B2F2F' },
      { name: 'Onyx', hex: '#000000' }
    ],
    sizes: ['M', 'L', 'XL'],
    images: [
      'https://images.unsplash.com/photo-1507679799987-c73779587ccf?auto=format&fit=crop&w=800&q=80',
      'https://images.unsplash.com/photo-1492562080023-ab3db95bfbce?auto=format&fit=crop&w=800&q=80'
    ],
    description: 'Supple nappa leather constructed with sharp peak lapels and a semi-fitted silhouette. Designed to age beautifully with time while offering modern urban elegance.',
    isNew: false
  },
  {
    id: 'prod-4',
    name: 'Cashmere Ribbed Turtleneck Sweater',
    category: 'Women',
    price: 295,
    originalPrice: null,
    rating: 4.7,
    reviewsCount: 56,
    badge: 'Bestseller',
    colors: [
      { name: 'Ivory', hex: '#FFFFF0' },
      { name: 'Oatmeal', hex: '#E3D9C6' },
      { name: 'Slate Gray', hex: '#708090' }
    ],
    sizes: ['XS', 'S', 'M', 'L', 'XL'],
    images: [
      'https://images.unsplash.com/photo-1576995853123-5a10305d93c0?auto=format&fit=crop&w=800&q=80',
      'https://images.unsplash.com/photo-1620799140408-edc6dcb6d633?auto=format&fit=crop&w=800&q=80'
    ],
    description: 'Pure 100% Mongolian grade-A cashmere knit with ultra-soft ribbing at cuffs and hem. The ultimate minimalist layering piece for cold-weather chic.',
    isNew: false
  },
  {
    id: 'prod-5',
    name: 'Monogram Sculptural Leather Tote',
    category: 'Accessories',
    price: 340,
    originalPrice: null,
    rating: 4.9,
    reviewsCount: 31,
    badge: 'New',
    colors: [
      { name: 'Cognac', hex: '#9A463D' },
      { name: 'Black', hex: '#111111' }
    ],
    sizes: ['One Size'],
    images: [
      'https://images.unsplash.com/photo-1584917865442-de89df76afd3?auto=format&fit=crop&w=800&q=80',
      'https://images.unsplash.com/photo-1590874103328-eac38a683ce7?auto=format&fit=crop&w=800&q=80'
    ],
    description: 'Architectural silhouette carved from full-grain vegetable-tanned leather. Includes detachable micro pouch and magnetic clasp hardware.',
    isNew: true
  },
  {
    id: 'prod-6',
    name: 'Minimalist Pleated Trousers',
    category: 'Men',
    price: 210,
    originalPrice: 260,
    rating: 4.6,
    reviewsCount: 19,
    badge: 'Sale',
    colors: [
      { name: 'Sand', hex: '#D2B48C' },
      { name: 'Navy', hex: '#000080' }
    ],
    sizes: ['S', 'M', 'L', 'XL'],
    images: [
      'https://images.unsplash.com/photo-1479064555552-3ef4979f8908?auto=format&fit=crop&w=800&q=80',
      'https://images.unsplash.com/photo-1617137984095-74e4e5e3613f?auto=format&fit=crop&w=800&q=80'
    ],
    description: 'High-waisted relaxed tailored trousers cut from breathable virgin wool twill. Double front pleats create a graceful, fluid drape with everyday movement.',
    isNew: false
  },
  {
    id: 'prod-7',
    name: 'Polarized Geometric Sunglasses',
    category: 'Accessories',
    price: 180,
    originalPrice: null,
    rating: 4.8,
    reviewsCount: 64,
    badge: 'Bestseller',
    colors: [
      { name: 'Tortoiseshell', hex: '#3E2723' },
      { name: 'Black Amber', hex: '#212121' }
    ],
    sizes: ['One Size'],
    images: [
      'https://images.unsplash.com/photo-1511499767150-a48a237f0083?auto=format&fit=crop&w=800&q=80',
      'https://images.unsplash.com/photo-1577803645773-f96470509666?auto=format&fit=crop&w=800&q=80'
    ],
    description: 'Japanese acetate frames fitted with UV400 anti-reflective polarized lenses. Features custom brass keyhole bridge detail and subtle laser-etched branding.',
    isNew: false
  },
  {
    id: 'prod-8',
    name: 'Silk Print Square Scarf',
    category: 'Accessories',
    price: 135,
    originalPrice: 160,
    rating: 4.7,
    reviewsCount: 14,
    badge: 'Sale',
    colors: [
      { name: 'Terracotta Print', hex: '#CC5500' }
    ],
    sizes: ['One Size'],
    images: [
      'https://images.unsplash.com/photo-1601924994987-69e26d50dc26?auto=format&fit=crop&w=800&q=80',
      'https://images.unsplash.com/photo-1584030373081-f37b7bb33805?auto=format&fit=crop&w=800&q=80'
    ],
    description: 'Hand-rolled 100% mulberry silk scarf adorned with bespoke hand-drawn botanical illustrations. Versatile styling around neck, head, or handbag straps.',
    isNew: false
  }
];

const LOOKBOOK_ITEMS = [
  {
    id: 1,
    title: 'Autumn Atelier Collection',
    subtitle: 'Rich textures, structured tailoring, and warm earthy palettes.',
    image: 'https://images.unsplash.com/photo-1490481651871-ab68de25d43d?auto=format&fit=crop&w=1200&q=80',
    hotspots: [
      { x: '35%', y: '40%', productId: 'prod-2', name: 'Wool Coat' },
      { x: '65%', y: '70%', productId: 'prod-5', name: 'Leather Tote' }
    ]
  },
  {
    id: 2,
    title: 'Monochrome Evening Wear',
    subtitle: 'High contrast elegance designed for unforgettable moonlit encounters.',
    image: 'https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=1200&q=80',
    hotspots: [
      { x: '45%', y: '35%', productId: 'prod-1', name: 'Satin Midi Dress' }
    ]
  }
];

const TESTIMONIALS = [
  {
    id: 1,
    name: 'Victoria Sterling',
    role: 'Fashion Director & Stylist',
    comment: 'VOGUE & THREAD delivers unmatched craftsmanship. The wool coat and silk wrap dress have become non-negotiable staples in my capsule wardrobe.',
    rating: 5,
    location: 'London, UK'
  },
  {
    id: 2,
    name: 'Julian Vance',
    role: 'Architect & Collector',
    comment: 'The attention to drape and fabric weight is extraordinary. Shipping was effortlessly fast, and the unboxing packaging feels like true haute couture.',
    rating: 5,
    location: 'New York, USA'
  },
  {
    id: 3,
    name: 'Elena Rostova',
    role: 'Creative Consultant',
    comment: 'Rarely do you find luxury online shopping that balances aesthetics with seamless user experience like VOGUE & THREAD. A 10/10 shopping experience.',
    rating: 5,
    location: 'Milan, Italy'
  }
];

export default function App() {
  // Navigation & Filtering
  const [selectedCategory, setSelectedCategory] = useState('All');
  const [searchQuery, setSearchQuery] = useState('');
  const [priceRange, setPriceRange] = useState(700);
  const [sortBy, setSortBy] = useState('featured');
  
  // Shopping Cart & Wishlist
  const [cart, setCart] = useState([]);
  const [wishlist, setWishlist] = useState([]);
  const [isCartOpen, setIsCartOpen] = useState(false);
  const [isWishlistOnly, setIsWishlistOnly] = useState(false);
  
  // Modals & Drawers
  const [selectedProduct, setSelectedProduct] = useState(null);
  const [isCheckoutOpen, setIsCheckoutOpen] = useState(false);
  const [checkoutStep, setCheckoutStep] = useState(1); // 1: Info, 2: Payment, 3: Success
  const [promoCode, setPromoCode] = useState('');
  const [appliedDiscount, setAppliedDiscount] = useState(0);
  const [newsletterEmail, setNewsletterEmail] = useState('');
  const [newsletterSubscribed, setNewsletterSubscribed] = useState(false);
  
  // Hero Slider State
  const [currentHeroSlide, setCurrentHeroSlide] = useState(0);
  const [mobileMenuOpen, setMobileMenuOpen] = useState(false);

  const heroSlides = [
    {
      title: 'REDEFINING MODERN ELEGANCE',
      subtitle: 'Discover the Autumn/Winter Haute Couture Capsule.',
      image: 'https://images.unsplash.com/photo-1469334031218-e382a71b716b?auto=format&fit=crop&w=1600&q=80',
      cta: 'Explore Collection'
    },
    {
      title: 'ARCHITECTURAL TAILORING',
      subtitle: 'Clean cut silhouettes sculpted from Italian wools and fine silks.',
      image: 'https://images.unsplash.com/photo-1441984904996-e0b6ba687e04?auto=format&fit=crop&w=1600&q=80',
      cta: 'Shop Tailoring'
    }
  ];

  // Auto Hero Slide Timer
  useEffect(() => {
    const timer = setInterval(() => {
      setCurrentHeroSlide((prev) => (prev + 1) % heroSlides.length);
    }, 6000);
    return () => clearInterval(timer);
  }, [heroSlides.length]);

  const filteredProducts = useMemo(() => {
    return INITIAL_PRODUCTS.filter((product) => {
      // Category Filter
      const matchesCategory = 
        selectedCategory === 'All' ? true :
        selectedCategory === 'Sale' ? product.originalPrice !== null :
        selectedCategory === 'New Arrivals' ? product.isNew :
        product.category === selectedCategory;

      // Search Query Filter
      const matchesSearch = product.name.toLowerCase().includes(searchQuery.toLowerCase()) ||
                            product.description.toLowerCase().includes(searchQuery.toLowerCase()) ||
                            product.category.toLowerCase().includes(searchQuery.toLowerCase());

      // Price Range Filter
      const matchesPrice = product.price <= priceRange;

      // Wishlist Only Filter toggle
      const matchesWishlist = isWishlistOnly ? wishlist.includes(product.id) : true;

      return matchesCategory && matchesSearch && matchesPrice && matchesWishlist;
    }).sort((a, b) => {
      if (sortBy === 'price-low') return a.price - b.price;
      if (sortBy === 'price-high') return b.price - a.price;
      if (sortBy === 'rating') return b.rating - a.rating;
      return 0; // Default featured
    });
  }, [selectedCategory, searchQuery, priceRange, sortBy, isWishlistOnly, wishlist]);

  const addToCart = (product, size = null, color = null) => {
    const selectedSize = size || product.sizes[0];
    const selectedColor = color || product.colors[0].name;

    setCart((prevCart) => {
      const existingIndex = prevCart.findIndex(
        item => item.id === product.id && item.size === selectedSize && item.color === selectedColor
      );

      if (existingIndex > -1) {
        const updated = [...prevCart];
        updated[existingIndex].quantity += 1;
        return updated;
      } else {
        return [...prevCart, { ...product, size: selectedSize, color: selectedColor, quantity: 1 }];
      }
    });

    setIsCartOpen(true);
  };

  const updateQuantity = (index, delta) => {
    setCart((prevCart) => {
      const updated = [...prevCart];
      const newQty = updated[index].quantity + delta;
      if (newQty <= 0) {
        return updated.filter((_, i) => i !== index);
      }
      updated[index].quantity = newQty;
      return updated;
    });
  };

  const removeFromCart = (index) => {
    setCart((prevCart) => prevCart.filter((_, i) => i !== index));
  };

  const toggleWishlist = (productId, e) => {
    if (e) e.stopPropagation();
    setWishlist((prev) => 
      prev.includes(productId) ? prev.filter(id => id !== productId) : [...prev, productId]
    );
  };

  const cartSubtotal = cart.reduce((sum, item) => sum + item.price * item.quantity, 0);
  const discountAmount = (cartSubtotal * appliedDiscount);
  const cartTotal = Math.max(0, cartSubtotal - discountAmount);
  const freeShippingThreshold = 150;
  const shippingProgress = Math.min(100, (cartSubtotal / freeShippingThreshold) * 100);

  const applyPromoCode = (e) => {
    e.preventDefault();
    if (promoCode.toUpperCase() === 'VOGUE10') {
      setAppliedDiscount(0.10);
    } else if (promoCode.toUpperCase() === 'LUXURY20') {
      setAppliedDiscount(0.20);
    } else {
      alert('Invalid promo code. Try "VOGUE10" or "LUXURY20"');
    }
  };

  const handleNewsletterSubmit = (e) => {
    e.preventDefault();
    if (newsletterEmail) {
      setNewsletterSubscribed(true);
      setTimeout(() => setNewsletterSubscribed(false), 5000);
      setNewsletterEmail('');
    }
  };

  return (
    <div className="min-h-screen bg-stone-50 text-stone-900 font-sans selection:bg-stone-900 selection:text-stone-100">
      
      {}
      <div className="bg-stone-900 text-stone-300 text-xs py-2 px-4 text-center tracking-widest uppercase font-light border-b border-stone-800 flex justify-between items-center px-6">
        <span className="hidden md:inline">Complimentary Worldwide Express Shipping on Orders Over $150</span>
        <span className="mx-auto md:mx-0">Code 'LUXURY20' for 20% Off New Season Collection</span>
        <div className="hidden md:flex items-center gap-4">
          <select className="bg-transparent text-stone-300 outline-none cursor-pointer hover:text-white transition">
            <option value="USD">USD ($)</option>
            <option value="EUR">EUR (€)</option>
            <option value="GBP">GBP (£)</option>
          </select>
        </div>
      </div>

      {}
      <header className="sticky top-0 z-40 bg-white/90 backdrop-blur-md border-b border-stone-200 transition-all">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
          
          {/* Mobile Hamburger Toggle */}
          <button 
            onClick={() => setMobileMenuOpen(!mobileMenuOpen)} 
            className="lg:hidden p-2 text-stone-800 hover:text-stone-600 focus:outline-none"
          >
            {mobileMenuOpen ? <X size={24} /> : <Menu size={24} />}
          </button>

          {/* Navigation Links */}
          <nav className="hidden lg:flex items-center space-x-8 text-xs uppercase tracking-widest font-medium">
            {['All', 'New Arrivals', 'Women', 'Men', 'Accessories', 'Sale'].map((cat) => (
              <button
                key={cat}
                onClick={() => {
                  setSelectedCategory(cat);
                  setIsWishlistOnly(false);
                }}
                className={`transition-colors py-2 border-b-2 ${
                  selectedCategory === cat && !isWishlistOnly
                    ? 'border-stone-900 text-stone-900 font-semibold' 
                    : 'border-transparent text-stone-600 hover:text-stone-900'
                }`}
              >
                {cat}
              </button>
            ))}
          </nav>

          {/* Brand Logo */}
          <div className="text-center cursor-pointer" onClick={() => { setSelectedCategory('All'); setIsWishlistOnly(false); }}>
            <h1 className="text-2xl md:text-3xl font-serif tracking-widest text-stone-900 font-bold uppercase">
              Vogue & Thread
            </h1>
            <p className="text-[9px] tracking-[0.3em] uppercase text-stone-500 font-sans">Haute Couture</p>
          </div>

          {/* Right Action Icons */}
          <div className="flex items-center space-x-5">
            {/* Search Input Bar Desktop */}
            <div className="relative hidden md:block w-48 lg:w-64">
              <input
                type="text"
                placeholder="Search luxury fashion..."
                value={searchQuery}
                onChange={(e) => setSearchQuery(e.target.value)}
                className="w-full bg-stone-100 text-xs py-2 pl-8 pr-4 rounded-full border border-transparent focus:border-stone-400 focus:bg-white focus:outline-none transition-all"
              />
              <Search className="absolute left-2.5 top-2.5 text-stone-400" size={14} />
              {searchQuery && (
                <button onClick={() => setSearchQuery('')} className="absolute right-2.5 top-2.5 text-stone-400 hover:text-stone-600">
                  <X size={12} />
                </button>
              )}
            </div>

            {/* Wishlist Button */}
            <button 
              onClick={() => setIsWishlistOnly(!isWishlistOnly)}
              className={`relative p-2 rounded-full transition ${isWishlistOnly ? 'bg-stone-900 text-white' : 'text-stone-800 hover:bg-stone-100'}`}
              title="View Wishlist"
            >
              <Heart size={20} className={wishlist.length > 0 && !isWishlistOnly ? "fill-stone-900 text-stone-900" : ""} />
              {wishlist.length > 0 && (
                <span className={`absolute -top-1 -right-1 text-[10px] w-4 h-4 rounded-full flex items-center justify-center font-bold ${isWishlistOnly ? 'bg-amber-500 text-stone-900' : 'bg-stone-900 text-white'}`}>
                  {wishlist.length}
                </span>
              )}
            </button>

            {/* Account Icon */}
            <button className="text-stone-800 hover:text-stone-500 p-2 hidden sm:block">
              <User size={20} />
            </button>

            {/* Cart Drawer Trigger */}
            <button 
              onClick={() => setIsCartOpen(true)}
              className="relative p-2 text-stone-800 hover:text-stone-500 flex items-center gap-2"
            >
              <ShoppingBag size={20} />
              <span className="hidden sm:inline text-xs font-semibold tracking-wider">${cartSubtotal.toFixed(0)}</span>
              {cart.length > 0 && (
                <span className="absolute -top-1 -right-1 bg-amber-600 text-white text-[10px] w-4 h-4 rounded-full flex items-center justify-center font-bold">
                  {cart.reduce((a, b) => a + b.quantity, 0)}
                </span>
              )}
            </button>
          </div>
        </div>

        {/* Mobile Navigation Dropdown */}
        {mobileMenuOpen && (
          <div className="lg:hidden bg-white border-b border-stone-200 px-6 py-4 space-y-3">
            <div className="relative mb-4">
              <input
                type="text"
                placeholder="Search luxury fashion..."
                value={searchQuery}
                onChange={(e) => setSearchQuery(e.target.value)}
                className="w-full bg-stone-100 text-xs py-2 pl-8 pr-4 rounded-full border border-stone-200 focus:outline-none"
              />
              <Search className="absolute left-2.5 top-2.5 text-stone-400" size={14} />
            </div>
            <div className="flex flex-col space-y-2 text-xs uppercase tracking-widest font-medium">
              {['All', 'New Arrivals', 'Women', 'Men', 'Accessories', 'Sale'].map((cat) => (
                <button
                  key={cat}
                  onClick={() => {
                    setSelectedCategory(cat);
                    setIsWishlistOnly(false);
                    setMobileMenuOpen(false);
                  }}
                  className={`text-left py-2 border-b border-stone-100 ${selectedCategory === cat ? 'text-stone-900 font-bold' : 'text-stone-600'}`}
                >
                  {cat}
                </button>
              ))}
            </div>
          </div>
        )}
      </header>

      {}
      {!isWishlistOnly && (
        <section className="relative h-[75vh] min-h-[500px] w-full overflow-hidden bg-stone-900">
          {heroSlides.map((slide, idx) => (
            <div 
              key={idx}
              className={`absolute inset-0 transition-opacity duration-1000 ease-in-out ${
                idx === currentHeroSlide ? 'opacity-100 z-10' : 'opacity-0 z-0'
              }`}
            >
              <img 
                src={slide.image} 
                alt={slide.title} 
                className="w-full h-full object-cover object-center filter brightness-[0.75]"
              />
              <div className="absolute inset-0 flex flex-col justify-center items-center text-center text-white p-6 max-w-4xl mx-auto">
                <span className="text-xs uppercase tracking-[0.4em] mb-3 text-amber-200 font-semibold">Atelier 2026 Collection</span>
                <h2 className="text-4xl sm:text-6xl font-serif tracking-tight font-light mb-4 leading-tight">
                  {slide.title}
                </h2>
                <p className="text-stone-200 text-sm sm:text-lg max-w-xl font-light mb-8">
                  {slide.subtitle}
                </p>
                <button 
                  onClick={() => {
                    const catalogElement = document.getElementById('catalog-section');
                    if (catalogElement) catalogElement.scrollIntoView({ behavior: 'smooth' });
                  }}
                  className="bg-white text-stone-900 px-8 py-4 text-xs font-semibold uppercase tracking-widest hover:bg-stone-100 hover:scale-105 transition duration-300 shadow-xl flex items-center gap-3"
                >
                  {slide.cta} <ArrowRight size={16} />
                </button>
              </div>
            </div>
          ))}

          {/* Carousel Controls */}
          <button 
            onClick={() => setCurrentHeroSlide((prev) => (prev === 0 ? heroSlides.length - 1 : prev - 1))}
            className="absolute left-4 top-1/2 -translate-y-1/2 z-20 p-3 rounded-full bg-black/30 text-white hover:bg-black/60 transition"
          >
            <ChevronLeft size={20} />
          </button>
          <button 
            onClick={() => setCurrentHeroSlide((prev) => (prev + 1) % heroSlides.length)}
            className="absolute right-4 top-1/2 -translate-y-1/2 z-20 p-3 rounded-full bg-black/30 text-white hover:bg-black/60 transition"
          >
            <ChevronRight size={20} />
          </button>

          {/* Dots Indicator */}
          <div className="absolute bottom-6 left-1/2 -translate-x-1/2 z-20 flex gap-2">
            {heroSlides.map((_, i) => (
              <button
                key={i}
                onClick={() => setCurrentHeroSlide(i)}
                className={`w-2.5 h-2.5 rounded-full transition-all ${i === currentHeroSlide ? 'bg-white w-8' : 'bg-white/50'}`}
              />
            ))}
          </div>
        </section>
      )}

      {}
      <section className="bg-stone-100 border-y border-stone-200 py-8 px-4">
        <div className="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
          <div className="flex flex-col items-center">
            <Truck size={24} className="text-stone-800 mb-2" />
            <h4 className="text-xs uppercase tracking-widest font-semibold">Complimentary Express Shipping</h4>
            <p className="text-xs text-stone-500 mt-1">Delivered in custom luxury gift packaging.</p>
          </div>
          <div className="flex flex-col items-center">
            <ShieldCheck size={24} className="text-stone-800 mb-2" />
            <h4 className="text-xs uppercase tracking-widest font-semibold">Authenticity Guaranteed</h4>
            <p className="text-xs text-stone-500 mt-1">100% handcrafted in Italy & France.</p>
          </div>
          <div className="flex flex-col items-center">
            <RefreshCw size={24} className="text-stone-800 mb-2" />
            <h4 className="text-xs uppercase tracking-widest font-semibold">Effortless 30-Day Returns</h4>
            <p className="text-xs text-stone-500 mt-1">Pre-paid return labels included with every order.</p>
          </div>
        </div>
      </section>

      {}
      <main id="catalog-section" className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
        <div className="flex flex-col md:flex-row md:items-end justify-between border-b border-stone-200 pb-6 mb-8 gap-4">
          <div>
            <span className="text-xs text-stone-500 uppercase tracking-widest">
              {isWishlistOnly ? 'Your Saved Items' : `${selectedCategory} Collection`}
            </span>
            <h3 className="text-3xl font-serif text-stone-900 mt-1 font-light">
              {isWishlistOnly ? 'Saved Favorites' : `Curated Garments (${filteredProducts.length})`}
            </h3>
          </div>

          <div className="flex flex-wrap items-center gap-4 text-xs">
            {/* Price Filter Control */}
            <div className="flex items-center gap-3 bg-white px-4 py-2 rounded-full border border-stone-200">
              <span className="text-stone-500 uppercase tracking-wider">Max Price:</span>
              <span className="font-semibold text-stone-900">${priceRange}</span>
              <input
                type="range"
                min="100"
                max="800"
                step="50"
                value={priceRange}
                onChange={(e) => setPriceRange(Number(e.target.value))}
                className="w-24 accent-stone-900 cursor-pointer"
              />
            </div>

            {/* Sort Dropdown */}
            <div className="flex items-center gap-2 bg-white px-4 py-2 rounded-full border border-stone-200">
              <SlidersHorizontal size={14} className="text-stone-500" />
              <select 
                value={sortBy} 
                onChange={(e) => setSortBy(e.target.value)}
                className="bg-transparent outline-none cursor-pointer text-stone-800 font-medium"
              >
                <option value="featured">Sort by: Featured</option>
                <option value="price-low">Price: Low to High</option>
                <option value="price-high">Price: High to Low</option>
                <option value="rating">Highest Rated</option>
              </select>
            </div>
          </div>
        </div>

        {}
        {filteredProducts.length === 0 ? (
          <div className="text-center py-20 bg-white rounded-xl border border-stone-200">
            <Sparkles size={48} className="mx-auto text-stone-300 mb-4" />
            <h4 className="text-xl font-serif text-stone-700">No pieces found matching your criteria</h4>
            <p className="text-stone-500 text-xs mt-2 max-w-sm mx-auto">
              Try adjusting your price range filter, resetting your search, or selecting a different category.
            </p>
            <button
              onClick={() => {
                setSelectedCategory('All');
                setSearchQuery('');
                setPriceRange(800);
                setIsWishlistOnly(false);
              }}
              className="mt-6 px-6 py-2.5 bg-stone-900 text-white text-xs uppercase tracking-widest rounded shadow hover:bg-stone-800 transition"
            >
              Reset All Filters
            </button>
          </div>
        ) : (
          <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
            {filteredProducts.map((product) => {
              const isWishlisted = wishlist.includes(product.id);
              return (
                <div 
                  key={product.id} 
                  className="group relative bg-white rounded-lg border border-stone-100 overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 flex flex-col"
                >
                  {/* Badge */}
                  {product.badge && (
                    <span className={`absolute top-3 left-3 z-10 text-[10px] uppercase tracking-widest font-bold px-2.5 py-1 rounded-sm ${
                      product.badge === 'Sale' ? 'bg-amber-700 text-white' :
                      product.badge === 'New' ? 'bg-stone-900 text-white' : 'bg-stone-200 text-stone-800'
                    }`}>
                      {product.badge}
                    </span>
                  )}

                  {/* Wishlist Button */}
                  <button
                    onClick={(e) => toggleWishlist(product.id, e)}
                    className="absolute top-3 right-3 z-10 p-2 rounded-full bg-white/80 backdrop-blur-md hover:bg-white text-stone-800 transition shadow-sm"
                  >
                    <Heart size={16} className={isWishlisted ? 'fill-red-600 text-red-600' : 'text-stone-600'} />
                  </button>

                  {/* Product Image Preview */}
                  <div 
                    className="relative aspect-[3/4] bg-stone-100 overflow-hidden cursor-pointer"
                    onClick={() => setSelectedProduct(product)}
                  >
                    <img 
                      src={product.images[0]} 
                      alt={product.name} 
                      className="w-full h-full object-cover object-center group-hover:scale-105 transition-transform duration-700"
                    />
                    {product.images[1] && (
                      <img 
                        src={product.images[1]} 
                        alt={`${product.name} hover`} 
                        className="w-full h-full object-cover object-center absolute inset-0 opacity-0 group-hover:opacity-100 transition-opacity duration-500"
                      />
                    )}
                    
                    {/* Quick View Overlay */}
                    <div className="absolute inset-0 bg-black/20 opacity-0 group-hover:opacity-100 transition-opacity flex items-end p-4">
                      <button 
                        onClick={(e) => {
                          e.stopPropagation();
                          setSelectedProduct(product);
                        }}
                        className="w-full py-2.5 bg-white/90 backdrop-blur-md text-stone-900 text-xs uppercase tracking-widest font-semibold hover:bg-white transition shadow flex items-center justify-center gap-2"
                      >
                        <Eye size={14} /> Quick View
                      </button>
                    </div>
                  </div>

                  {/* Product Info */}
                  <div className="p-5 flex-1 flex flex-col justify-between">
                    <div>
                      <div className="flex items-center justify-between text-xs text-stone-400 mb-1">
                        <span>{product.category}</span>
                        <div className="flex items-center gap-1 text-amber-500">
                          <Star size={12} className="fill-amber-400 text-amber-400" />
                          <span className="text-stone-700 font-medium">{product.rating}</span>
                        </div>
                      </div>
                      <h4 
                        onClick={() => setSelectedProduct(product)}
                        className="font-serif text-stone-900 text-base font-normal hover:text-amber-800 transition cursor-pointer line-clamp-1"
                      >
                        {product.name}
                      </h4>
                      
                      {/* Price Display */}
                      <div className="mt-2 flex items-baseline gap-2">
                        <span className="text-sm font-semibold text-stone-900">${product.price}</span>
                        {product.originalPrice && (
                          <span className="text-xs text-stone-400 line-through">${product.originalPrice}</span>
                        )}
                      </div>
                    </div>

                    {/* Quick Add Button */}
                    <button
                      onClick={() => addToCart(product)}
                      className="mt-4 w-full py-2 bg-stone-900 text-white text-xs uppercase tracking-widest rounded hover:bg-amber-800 transition flex items-center justify-center gap-2"
                    >
                      <Plus size={14} /> Add to Bag
                    </button>
                  </div>
                </div>
              );
            })}
          </div>
        )}
      </main>

      {}
      {!isWishlistOnly && (
        <section className="bg-stone-900 text-stone-100 py-20 px-4 sm:px-6 lg:px-8 mt-12">
          <div className="max-w-7xl mx-auto">
            <div className="text-center max-w-2xl mx-auto mb-16">
              <span className="text-xs uppercase tracking-[0.3em] text-amber-300 font-semibold">Editorial Lookbook</span>
              <h3 className="text-3xl sm:text-4xl font-serif mt-2 font-light">Interactive Styling Gallery</h3>
              <p className="text-stone-400 text-xs mt-3 leading-relaxed">
                Hover over the interactive hotspots below to discover individual atelier pieces featured in our runway ensemble.
              </p>
            </div>

            <div className="grid grid-cols-1 lg:grid-cols-2 gap-12">
              {LOOKBOOK_ITEMS.map((item) => (
                <div key={item.id} className="relative rounded-lg overflow-hidden border border-stone-800 group">
                  <img src={item.image} alt={item.title} className="w-full h-[450px] object-cover filter brightness-[0.9]" />
                  <div className="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent p-6 flex flex-col justify-end">
                    <h4 className="text-xl font-serif text-white">{item.title}</h4>
                    <p className="text-xs text-stone-300 mt-1">{item.subtitle}</p>
                  </div>

                  {/* Hotspots */}
                  {item.hotspots.map((spot, i) => {
                    const targetProduct = INITIAL_PRODUCTS.find(p => p.id === spot.productId);
                    return (
                      <div 
                        key={i} 
                        style={{ left: spot.x, top: spot.y }} 
                        className="absolute -translate-x-1/2 -translate-y-1/2 group/spot"
                      >
                        <button className="w-6 h-6 rounded-full bg-white text-stone-900 flex items-center justify-center shadow-lg animate-pulse hover:scale-125 transition">
                          <Plus size={14} />
                        </button>
                        {targetProduct && (
                          <div className="absolute bottom-8 left-1/2 -translate-x-1/2 hidden group-hover/spot:flex bg-white text-stone-900 p-3 rounded shadow-2xl w-48 flex-col text-left z-30 pointer-events-auto">
                            <span className="text-[10px] uppercase text-stone-400 tracking-wider">Featured Item</span>
                            <span className="text-xs font-serif font-bold line-clamp-1">{targetProduct.name}</span>
                            <span className="text-xs font-semibold text-stone-900 mt-1">${targetProduct.price}</span>
                            <button 
                              onClick={() => setSelectedProduct(targetProduct)}
                              className="mt-2 text-[10px] uppercase tracking-widest bg-stone-900 text-white py-1 px-2 rounded text-center hover:bg-amber-800 transition"
                            >
                              View Item
                            </button>
                          </div>
                        )}
                      </div>
                    );
                  })}
                </div>
              ))}
            </div>
          </div>
        </section>
      )}

      {}
      {!isWishlistOnly && (
        <section className="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-12">
            <span className="text-xs uppercase tracking-[0.3em] text-stone-500 font-semibold">Client Stories</span>
            <h3 className="text-3xl font-serif text-stone-900 mt-2 font-light">Endorsed by Connoisseurs</h3>
          </div>

          <div className="grid grid-cols-1 md:grid-cols-3 gap-8">
            {TESTIMONIALS.map((t) => (
              <div key={t.id} className="bg-white p-8 rounded-lg border border-stone-200 shadow-sm flex flex-col justify-between">
                <div>
                  <div className="flex gap-1 text-amber-500 mb-4">
                    {[...Array(t.rating)].map((_, i) => (
                      <Star key={i} size={14} className="fill-amber-400 text-amber-400" />
                    ))}
                  </div>
                  <p className="text-stone-700 text-xs italic leading-relaxed">"{t.comment}"</p>
                </div>
                <div className="mt-6 pt-4 border-t border-stone-100">
                  <h5 className="text-xs font-bold text-stone-900 uppercase tracking-wider">{t.name}</h5>
                  <p className="text-[10px] text-stone-400">{t.role} — {t.location}</p>
                </div>
              </div>
            ))}
          </div>
        </section>
      )}

      {}
      {selectedProduct && (
        <div className="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/60 backdrop-blur-sm">
          <div className="bg-white rounded-xl max-w-4xl w-full overflow-hidden shadow-2xl relative max-h-[90vh] flex flex-col md:flex-row">
            <button 
              onClick={() => setSelectedProduct(null)}
              className="absolute top-4 right-4 z-20 p-2 rounded-full bg-stone-100 hover:bg-stone-200 text-stone-800 transition"
            >
              <X size={18} />
            </button>

            {/* Product Image Gallery in Modal */}
            <div className="md:w-1/2 bg-stone-100 relative min-h-[300px]">
              <img 
                src={selectedProduct.images[0]} 
                alt={selectedProduct.name} 
                className="w-full h-full object-cover"
              />
            </div>

            {/* Product Details Sidebar */}
            <div className="md:w-1/2 p-6 md:p-8 flex flex-col justify-between overflow-y-auto">
              <div>
                <span className="text-xs uppercase text-stone-400 tracking-widest">{selectedProduct.category}</span>
                <h3 className="text-2xl font-serif text-stone-900 mt-1">{selectedProduct.name}</h3>
                
                <div className="flex items-center gap-3 mt-3">
                  <span className="text-xl font-bold text-stone-900">${selectedProduct.price}</span>
                  {selectedProduct.originalPrice && (
                    <span className="text-sm text-stone-400 line-through">${selectedProduct.originalPrice}</span>
                  )}
                  <span className="ml-auto text-xs text-emerald-700 font-medium bg-emerald-50 px-2 py-0.5 rounded">In Stock</span>
                </div>

                <p className="text-stone-600 text-xs mt-4 leading-relaxed">
                  {selectedProduct.description}
                </p>

                {/* Color Swatch Selection */}
                <div className="mt-6">
                  <label className="text-xs uppercase font-semibold text-stone-700 tracking-wider block mb-2">Color Palette</label>
                  <div className="flex gap-3">
                    {selectedProduct.colors.map((col, idx) => (
                      <button
                        key={idx}
                        className="w-7 h-7 rounded-full border-2 border-white ring-1 ring-stone-300 flex items-center justify-center focus:ring-stone-900 transition"
                        style={{ backgroundColor: col.hex }}
                        title={col.name}
                      />
                    ))}
                  </div>
                </div>

                {/* Size Selection Pills */}
                <div className="mt-6">
                  <div className="flex justify-between items-center mb-2">
                    <label className="text-xs uppercase font-semibold text-stone-700 tracking-wider">Select Size</label>
                    <button className="text-[10px] text-stone-500 underline uppercase tracking-wider">Size Guide</button>
                  </div>
                  <div className="flex flex-wrap gap-2">
                    {selectedProduct.sizes.map((sz) => (
                      <button
                        key={sz}
                        className="px-4 py-2 border border-stone-200 text-xs rounded hover:border-stone-900 hover:bg-stone-900 hover:text-white transition font-medium"
                      >
                        {sz}
                      </button>
                    ))}
                  </div>
                </div>
              </div>

              {/* Modal Actions */}
              <div className="mt-8 pt-6 border-t border-stone-100 flex gap-3">
                <button
                  onClick={() => {
                    addToCart(selectedProduct);
                    setSelectedProduct(null);
                  }}
                  className="flex-1 py-3 bg-stone-900 text-white text-xs uppercase tracking-widest font-semibold rounded hover:bg-amber-800 transition flex items-center justify-center gap-2"
                >
                  <ShoppingBag size={16} /> Add to Cart
                </button>
                <button
                  onClick={(e) => toggleWishlist(selectedProduct.id, e)}
                  className="p-3 border border-stone-200 rounded hover:border-stone-900 text-stone-800 transition"
                >
                  <Heart size={18} className={wishlist.includes(selectedProduct.id) ? 'fill-red-600 text-red-600' : ''} />
                </button>
              </div>
            </div>
          </div>
        </div>
      )}

      {}
      {isCartOpen && (
        <div className="fixed inset-0 z-50 overflow-hidden bg-black/50 backdrop-blur-xs">
          <div className="absolute inset-y-0 right-0 max-w-full flex pl-10">
            <div className="w-screen max-w-md bg-white shadow-2xl flex flex-col justify-between">
              
              {/* Cart Drawer Header */}
              <div className="p-6 border-b border-stone-200 flex items-center justify-between">
                <div className="flex items-center gap-2">
                  <ShoppingBag size={20} className="text-stone-900" />
                  <h3 className="font-serif text-lg text-stone-900 font-semibold">Shopping Bag ({cart.length})</h3>
                </div>
                <button 
                  onClick={() => setIsCartOpen(false)}
                  className="p-2 text-stone-400 hover:text-stone-800 rounded-full hover:bg-stone-100 transition"
                >
                  <X size={20} />
                </button>
              </div>

              {/* Free Shipping Progress */}
              <div className="bg-stone-50 p-4 border-b border-stone-200">
                <div className="flex justify-between text-xs text-stone-600 mb-1 font-medium">
                  <span>
                    {cartSubtotal >= freeShippingThreshold 
                      ? ' You unlocked Complimentary Express Shipping!' 
                      : `Add $${(freeShippingThreshold - cartSubtotal).toFixed(2)} more for Free Shipping`}
                  </span>
                </div>
                <div className="w-full bg-stone-200 h-1.5 rounded-full overflow-hidden">
                  <div 
                    className="bg-stone-900 h-full transition-all duration-500" 
                    style={{ width: `${shippingProgress}%` }}
                  />
                </div>
              </div>

              {/* Cart Items List */}
              <div className="flex-1 overflow-y-auto p-6 space-y-6">
                {cart.length === 0 ? (
                  <div className="text-center py-12">
                    <ShoppingBag size={40} className="mx-auto text-stone-300 mb-3" />
                    <p className="text-sm font-serif text-stone-600">Your shopping bag is currently empty.</p>
                    <button
                      onClick={() => setIsCartOpen(false)}
                      className="mt-4 text-xs uppercase tracking-widest text-stone-900 font-bold underline"
                    >
                      Start Shopping
                    </button>
                  </div>
                ) : (
                  cart.map((item, idx) => (
                    <div key={idx} className="flex gap-4 border-b border-stone-100 pb-4">
                      <img src={item.images[0]} alt={item.name} className="w-20 h-24 object-cover rounded bg-stone-100" />
                      <div className="flex-1 flex flex-col justify-between">
                        <div>
                          <div className="flex justify-between items-start">
                            <h5 className="font-serif text-sm font-medium text-stone-900">{item.name}</h5>
                            <button onClick={() => removeFromCart(idx)} className="text-stone-400 hover:text-red-600 text-xs">
                              <X size={14} />
                            </button>
                          </div>
                          <p className="text-[11px] text-stone-500 mt-0.5">Size: {item.size} | Color: {item.color}</p>
                          <span className="text-xs font-semibold text-stone-900 mt-1 block">${item.price}</span>
                        </div>

                        <div className="flex items-center gap-3">
                          <div className="flex items-center border border-stone-200 rounded">
                            <button onClick={() => updateQuantity(idx, -1)} className="px-2 py-1 text-stone-600 hover:bg-stone-100">
                              <Minus size={12} />
                            </button>
                            <span className="px-2 text-xs font-semibold">{item.quantity}</span>
                            <button onClick={() => updateQuantity(idx, 1)} className="px-2 py-1 text-stone-600 hover:bg-stone-100">
                              <Plus size={12} />
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  ))
                )}
              </div>

              {/* Cart Drawer Footer & Checkout Action */}
              {cart.length > 0 && (
                <div className="p-6 border-t border-stone-200 bg-stone-50">
                  {/* Promo Code Input */}
                  <form onSubmit={applyPromoCode} className="flex gap-2 mb-4">
                    <input 
                      type="text" 
                      placeholder="Promo Code (e.g. LUXURY20)" 
                      value={promoCode}
                      onChange={(e) => setPromoCode(e.target.value)}
                      className="flex-1 text-xs px-3 py-2 bg-white border border-stone-200 rounded uppercase tracking-wider focus:outline-none"
                    />
                    <button type="submit" className="px-3 py-2 bg-stone-200 text-stone-800 text-xs uppercase font-semibold rounded hover:bg-stone-300">
                      Apply
                    </button>
                  </form>

                  <div className="space-y-2 text-xs text-stone-600 mb-4">
                    <div className="flex justify-between">
                      <span>Subtotal</span>
                      <span className="font-semibold text-stone-900">${cartSubtotal.toFixed(2)}</span>
                    </div>
                    {appliedDiscount > 0 && (
                      <div className="flex justify-between text-amber-700 font-medium">
                        <span>Discount ({(appliedDiscount * 100)}%)</span>
                        <span>-${discountAmount.toFixed(2)}</span>
                      </div>
                    )}
                    <div className="flex justify-between text-sm font-bold text-stone-900 pt-2 border-t border-stone-200">
                      <span>Total</span>
                      <span>${cartTotal.toFixed(2)}</span>
                    </div>
                  </div>

                  <button 
                    onClick={() => {
                      setIsCartOpen(false);
                      setIsCheckoutOpen(true);
                      setCheckoutStep(1);
                    }}
                    className="w-full py-3.5 bg-stone-900 text-white text-xs uppercase tracking-widest font-semibold rounded hover:bg-amber-800 transition flex items-center justify-center gap-2 shadow-lg"
                  >
                    Proceed to Checkout <ArrowRight size={14} />
                  </button>
                </div>
              )}
            </div>
          </div>
        </div>
      )}

      {}
      {isCheckoutOpen && (
        <div className="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/60 backdrop-blur-sm">
          <div className="bg-white rounded-xl max-w-2xl w-full p-6 md:p-8 shadow-2xl relative max-h-[90vh] overflow-y-auto">
            <button 
              onClick={() => setIsCheckoutOpen(false)}
              className="absolute top-4 right-4 text-stone-400 hover:text-stone-800"
            >
              <X size={20} />
            </button>

            {/* Checkout Progress Tabs */}
            <div className="flex items-center justify-between mb-8 border-b border-stone-200 pb-4">
              <div className={`flex items-center gap-2 text-xs font-semibold ${checkoutStep >= 1 ? 'text-stone-900' : 'text-stone-400'}`}>
                <span className="w-5 h-5 rounded-full bg-stone-900 text-white flex items-center justify-center text-[10px]">1</span>
                <span>Shipping</span>
              </div>
              <ChevronRight size={14} className="text-stone-300" />
              <div className={`flex items-center gap-2 text-xs font-semibold ${checkoutStep >= 2 ? 'text-stone-900' : 'text-stone-400'}`}>
                <span className={`w-5 h-5 rounded-full flex items-center justify-center text-[10px] ${checkoutStep >= 2 ? 'bg-stone-900 text-white' : 'bg-stone-200 text-stone-600'}`}>2</span>
                <span>Payment</span>
              </div>
              <ChevronRight size={14} className="text-stone-300" />
              <div className={`flex items-center gap-2 text-xs font-semibold ${checkoutStep === 3 ? 'text-stone-900' : 'text-stone-400'}`}>
                <span className={`w-5 h-5 rounded-full flex items-center justify-center text-[10px] ${checkoutStep === 3 ? 'bg-stone-900 text-white' : 'bg-stone-200 text-stone-600'}`}>3</span>
                <span>Confirmation</span>
              </div>
            </div>

            {/* Step 1: Shipping Address Form */}
            {checkoutStep === 1 && (
              <form onSubmit={(e) => { e.preventDefault(); setCheckoutStep(2); }} className="space-y-4">
                <h4 className="font-serif text-lg text-stone-900 font-semibold mb-2">Shipping Details</h4>
                <div className="grid grid-cols-2 gap-4">
                  <input required type="text" placeholder="First Name" className="text-xs p-3 border border-stone-200 rounded outline-none focus:border-stone-900" />
                  <input required type="text" placeholder="Last Name" className="text-xs p-3 border border-stone-200 rounded outline-none focus:border-stone-900" />
                </div>
                <input required type="email" placeholder="Email Address for Tracking" className="w-full text-xs p-3 border border-stone-200 rounded outline-none focus:border-stone-900" />
                <input required type="text" placeholder="Street Address" className="w-full text-xs p-3 border border-stone-200 rounded outline-none focus:border-stone-900" />
                <div className="grid grid-cols-3 gap-4">
                  <input required type="text" placeholder="City" className="text-xs p-3 border border-stone-200 rounded outline-none focus:border-stone-900" />
                  <input required type="text" placeholder="Country" className="text-xs p-3 border border-stone-200 rounded outline-none focus:border-stone-900" />
                  <input required type="text" placeholder="Postal Code" className="text-xs p-3 border border-stone-200 rounded outline-none focus:border-stone-900" />
                </div>
                <button type="submit" className="w-full mt-6 py-3 bg-stone-900 text-white text-xs uppercase tracking-widest font-semibold rounded hover:bg-amber-800 transition">
                  Continue to Payment
                </button>
              </form>
            )}

            {/* Step 2: Payment Simulation Form */}
            {checkoutStep === 2 && (
              <form onSubmit={(e) => { e.preventDefault(); setCheckoutStep(3); setCart([]); }} className="space-y-4">
                <h4 className="font-serif text-lg text-stone-900 font-semibold mb-2">Secure Payment</h4>
                <div className="p-4 border border-stone-200 rounded bg-stone-50 flex items-center justify-between mb-4">
                  <div className="flex items-center gap-3">
                    <CreditCard size={20} className="text-stone-700" />
                    <span className="text-xs font-semibold text-stone-800">Credit Card / Debit Card</span>
                  </div>
                  <Lock size={14} className="text-stone-400" />
                </div>
                <input required type="text" placeholder="Cardholder Name" className="w-full text-xs p-3 border border-stone-200 rounded outline-none focus:border-stone-900" />
                <input required type="text" placeholder="Card Number (4242 ...)" defaultValue="4242 •••• •••• 4242" className="w-full text-xs p-3 border border-stone-200 rounded outline-none focus:border-stone-900" />
                <div className="grid grid-cols-2 gap-4">
                  <input required type="text" placeholder="MM/YY" defaultValue="12/28" className="text-xs p-3 border border-stone-200 rounded outline-none focus:border-stone-900" />
                  <input required type="text" placeholder="CVC" defaultValue="888" className="text-xs p-3 border border-stone-200 rounded outline-none focus:border-stone-900" />
                </div>
                <div className="pt-4 border-t border-stone-100 flex justify-between items-center text-sm font-bold">
                  <span>Total Amount Due:</span>
                  <span>${cartTotal.toFixed(2)}</span>
                </div>
                <button type="submit" className="w-full mt-4 py-3.5 bg-emerald-800 text-white text-xs uppercase tracking-widest font-semibold rounded hover:bg-emerald-900 transition flex items-center justify-center gap-2">
                  <Lock size={14} /> Complete Order (${cartTotal.toFixed(2)})
                </button>
              </form>
            )}

            {/* Step 3: Success Confirmation */}
            {checkoutStep === 3 && (
              <div className="text-center py-8 space-y-4">
                <div className="w-16 h-16 bg-emerald-100 text-emerald-700 rounded-full flex items-center justify-center mx-auto mb-4">
                  <Check size={32} />
                </div>
                <h4 className="font-serif text-2xl text-stone-900">Thank You for Your Order!</h4>
                <p className="text-xs text-stone-500 max-w-md mx-auto">
                  Order #VT-{Math.floor(100000 + Math.random() * 900000)} has been placed successfully. A confirmation email with express courier tracking details has been sent to your inbox.
                </p>
                <button 
                  onClick={() => setIsCheckoutOpen(false)} 
                  className="mt-6 px-8 py-3 bg-stone-900 text-white text-xs uppercase tracking-widest rounded hover:bg-amber-800 transition"
                >
                  Continue Shopping
                </button>
              </div>
            )}
          </div>
        </div>
      )}

      {}
      <footer className="bg-stone-900 text-stone-300 pt-16 pb-8 border-t border-stone-800">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-4 gap-12 mb-12">
          
          {/* Brand Info */}
          <div>
            <h2 className="text-xl font-serif text-white uppercase tracking-widest font-bold">VOGUE & THREAD</h2>
            <p className="text-xs text-stone-400 mt-3 leading-relaxed">
              Curated luxury wardrobe staples designed with timeless craftsmanship, organic materials, and sustainable modern aesthetics.
            </p>
          </div>

          {/* Quick Links */}
          <div>
            <h5 className="text-xs uppercase tracking-widest font-semibold text-white mb-4">Collections</h5>
            <ul className="space-y-2 text-xs text-stone-400">
              <li><a href="#" className="hover:text-white transition">New Arrivals 2026</a></li>
              <li><a href="#" className="hover:text-white transition">Women's Haute Couture</a></li>
              <li><a href="#" className="hover:text-white transition">Men's Tailored Suits</a></li>
              <li><a href="#" className="hover:text-white transition">Leather Accessories</a></li>
            </ul>
          </div>

          {/* Client Service */}
          <div>
            <h5 className="text-xs uppercase tracking-widest font-semibold text-white mb-4">Client Care</h5>
            <ul className="space-y-2 text-xs text-stone-400">
              <li><a href="#" className="hover:text-white transition">Complimentary Shipping & Returns</a></li>
              <li><a href="#" className="hover:text-white transition">Garment Care Guide</a></li>
              <li><a href="#" className="hover:text-white transition">Bespoke Fitting Consultations</a></li>
              <li><a href="#" className="hover:text-white transition">Store Locator</a></li>
            </ul>
          </div>

          {/* Newsletter Signup */}
          <div>
            <h5 className="text-xs uppercase tracking-widest font-semibold text-white mb-4">Atelier Newsletter</h5>
            <p className="text-xs text-stone-400 mb-3">Subscribe to receive private invitations to runway previews and capsule collection drops.</p>
            
            <form onSubmit={handleNewsletterSubmit} className="space-y-2">
              <input
                type="email"
                required
                placeholder="Enter your email..."
                value={newsletterEmail}
                onChange={(e) => setNewsletterEmail(e.target.value)}
                className="w-full bg-stone-800 text-xs text-stone-100 px-3 py-2.5 rounded border border-stone-700 focus:outline-none focus:border-stone-400"
              />
              <button type="submit" className="w-full py-2.5 bg-white text-stone-900 text-xs uppercase tracking-widest font-bold rounded hover:bg-stone-200 transition">
                Subscribe
              </button>
            </form>
            
            {newsletterSubscribed && (
              <p className="text-xs text-emerald-400 mt-2 font-medium">✨ Welcome to the Vogue & Thread Atelier list.</p>
            )}
          </div>
        </div>

        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 border-t border-stone-800 pt-8 flex flex-col sm:flex-row items-center justify-between text-[11px] text-stone-500 gap-4">
          <p>© 2026 VOGUE & THREAD Atelier Ltd. All rights reserved.</p>
          <div className="flex gap-6">
            <a href="#" className="hover:text-stone-300">Privacy Policy</a>
            <a href="#" className="hover:text-stone-300">Terms of Service</a>
            <a href="#" className="hover:text-stone-300">Cookies Settings</a>
          </div>
        </div>
      </footer>
    </div>
  );
}