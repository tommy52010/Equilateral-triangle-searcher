# Equilateral-triangle-searcher
import turtle,easygui
easygui.msgbox('Equilateral triangle searcher')
first_side = easygui.enterbox('Tell the first side of triangle:')
second_side = easygui.enterbox('Tell the second side of triangle:')
third_side = easygui.enterbox('Tell the second side of triangle:')
turtle.forward(int(first_side))
turtle.left(120)
turtle.forward(int(second_side))
turtle.left(120)
turtle.forward(int(third_side))
