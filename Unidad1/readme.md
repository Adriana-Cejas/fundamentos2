{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyPue9FegVi/hykWJpRwvErT",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/Adriana-Cejas/fundamentos2/blob/main/Unidad1/readme.md\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": 13,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "eMpwi7S3_dFH",
        "outputId": "f52ff3cb-d41b-48fb-c7f8-d9cc9b214415"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Dame la basase del triaungulo15\n",
            "Dame la altura del triangulo20\n",
            "El area del triaungulo es 150.0\n"
          ]
        }
      ],
      "source": [
        "base= input(\"Dame la basase del triaungulo\")\n",
        "altura= input(\"Dame la altura del triangulo\")\n",
        "area=(int(base)*int(altura))/2\n",
        "print(\"El area del triaungulo es\", area)\n"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "z = 10\n",
        "a = \"Hola\"\n",
        "print(z * a)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "aK-psLG-BGXs",
        "outputId": "ee268757-2ee2-4586-e62c-6b0fc698e13c"
      },
      "execution_count": 3,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "HolaHolaHolaHolaHolaHolaHolaHolaHolaHola\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "numero1= 20\n",
        "numero2= 40\n",
        "if numero1 > numero2:\n",
        "  print(\"El numero\",numero1,\"Es mayor que\",numero2)\n",
        "else:\n",
        "  print(\"El numero\",numero2,\"Es mayor que\",numero1)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "v09K1VvhBg7Z",
        "outputId": "e9c059ac-cf9a-4641-ef55-04b18b1b4a83"
      },
      "execution_count": 10,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "El numero 40 Es mayor que 20\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "x = 5\n",
        "X = \"Hola\"\n",
        "X = True\n",
        "print(\"El valor de x es\",X)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "LYUDcGEYB1FN",
        "outputId": "98503d6f-8ec6-44bb-be91-5315e3da8f0d"
      },
      "execution_count": 12,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "El valor de x es True\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "from google.colab import drive\n",
        "drive.mount('/content/drive')"
      ],
      "metadata": {
        "id": "QM2hmkFomT8q"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "variable1=70\n",
        "variable2= 50\n",
        "if variable1 > variable2\n"
      ],
      "metadata": {
        "id": "sy_9Riv1B5S2"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "edad= int(input(\"Dame tu edad\"))\n",
        "if edad <= 10:\n",
        "  print(\"Eres un niño\")\n",
        "elif edad <= 18:\n",
        " print(\"Eres un adolecente\")\n",
        "elif edad <= 30:\n",
        " print(\"Eres un adulto joven\")\n",
        "elif edad <= 65:\n",
        " print(\"Eres un adulto\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "jcGBMUdsCdVk",
        "outputId": "9ce49574-21bf-4018-9f33-3d042130ff7f"
      },
      "execution_count": 12,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Dame tu edad18\n",
            "Eres un adolecente\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "edad= int(input(\"Dame tu edad\"))\n",
        "if edad >=66:\n",
        "  print(\"Eres un adulto\")\n",
        "elif edad >=31 and edad <=65:\n",
        "  print(\"Eres un adulto joven\")\n",
        "elif edad >=19 and edad <=30:\n",
        "  print(\"Eres un adolecente\")\n",
        "elif edad >=11 and edad <=18:\n",
        "  print(\"Eres un niño\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "ljFJTheFEFJb",
        "outputId": "e210de26-6def-4acb-c192-00851751f6f6"
      },
      "execution_count": 11,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Dame tu edad45\n",
            "Eres un adulto joven\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "tabla= int(input(\"Dame la tabla de multiplicar\"))\n",
        "Limiteinicial= int(input(\"Dame el Limiteinicial\"))\n",
        "Limitefinal= int(input(\"Dame el Limitefinal\"))\n",
        "Incrementacion= 4\n",
        "for i in range(Limiteinicial, Limitefinal, Incrementacion):\n",
        "  print(tabla, \"x\", i, \"=\", tabla*i)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "0xCYuP5VIwU9",
        "outputId": "de01da87-791d-424a-c98a-dc4916d57a37"
      },
      "execution_count": 9,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Dame la tabla de multiplicar15\n",
            "Dame el Limiteinicial1\n",
            "Dame el Limitefinal11\n",
            "15 x 1 = 15\n",
            "15 x 5 = 75\n",
            "15 x 9 = 135\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "10 > 5  and 5 < 10"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "YmQ42t2_CKel",
        "outputId": "8aa6f24d-1497-44e2-b151-36a73e6c95eb"
      },
      "execution_count": 4,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "True"
            ]
          },
          "metadata": {},
          "execution_count": 4
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "10 > 5 and 5 > 10"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "uwm0YNpSCivZ",
        "outputId": "1f2b978c-4524-4f39-9814-afdf7e781f12"
      },
      "execution_count": 5,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "False"
            ]
          },
          "metadata": {},
          "execution_count": 5
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "10 > 5 or 5 > 10"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Nz2ZfKxpCqmu",
        "outputId": "5417535f-e6f7-45f2-b1d5-929821e1e8df"
      },
      "execution_count": 6,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "True"
            ]
          },
          "metadata": {},
          "execution_count": 6
        }
      ]
    }
  ]
}