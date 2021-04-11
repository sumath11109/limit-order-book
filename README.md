# limit-order-book
# market order 
def MarketOrder(action:str, quantity:float):
    order = Order()
    order.action = action
    print("order type is",mkt)
    order.totalQuantity = quantity
    return mkt
    
#limit order
def LimitOrder(action:str, quantity:float, limitPrice:float,price):
    order = Order()
    order.action = action
    order.orderType = “LMT”
    order.totalQuantity = quantity
    order.lmtPrice = limitPrice
    if price > limit price:
        print("insufficient funds")
    else:
        print("buy order)
    return order
    
#stop order
def stoporder(price,quantity,limitprice,no.of stocks):
if price>limit price:
   print("stop order")
elif quantity > no.of stocks:
   print("stop order")
else:
   print("book order")
