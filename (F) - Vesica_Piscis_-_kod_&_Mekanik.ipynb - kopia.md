


````python
{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
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
      "source": [
        "# RP9 — Nivå I: Primär struktur (Vesica Piscis)\n",
        "\n",
        "Denna notebook etablerar och demonstrerar Nivå I: Primär struktur.\n",
        "\n",
        "- Endast relationella nödvändigheter\n",
        "- Ingen fusion\n",
        "- Ingen sekundär kausalitet\n",
        "\n",
        "Instruktion:\n",
        "**Runtime → Run all**\n",
        "\n",
        "\n",
        "### **DEL 4 — Nivå II: Operativ & metodologisk tillämpning**\n",
        "\n",
        "> ---\n",
        ">\n",
        "> 19. **Vesica Piscis — kod & matematik**\n",
        ">     \n",
        ">\n",
        "> > ---\n",
        "> >\n",
        "> > **A – Endast funktionell manifestation**  \n",
        "> > Den kod som presenteras här visar Vesica Piscis som numerisk och geometrisk manifestation.  \n",
        "> > Den beräknar skärningspunkter och skaloberoende relationella kvoter utan fria parametrar.\n",
        "> >\n",
        "> > **B – Ingen semantisk tolkning**  \n",
        "> > Ingen symbolik, mening eller tolkning knyts till resultaten.  \n",
        "> > Koden redovisar endast råa numeriska och geometriska utdata.\n",
        "> >\n",
        "> > **C – Ingen etablering av grund**  \n",
        "> > Denna kod etablerar inte Vesica Piscis som struktur.  \n",
        "> > All grund för Vesica Piscis är fastställd före denna representation och påverkas inte av den.\n",
        "> >\n",
        "> > **D – Avgränsningsdeklaration (bindande)**  \n",
        "> > Denna kod representerar Vesica Piscis som sekundär manifestation.  \n",
        "> > Den introducerar inga axiom, utgör inget bevis och har ingen grundläggande funktion i RP9.  \n",
        "> > Den existerar uteslutande som operativ avbildning av redan låst struktur.\n",
        "> >\n",
        "---\n",
        "\n",
        "\n",
        "✅ Åtgärd (bindande)\n",
        "\n",
        "Ersätt eller komplettera cellen så att följande tre punkter är explicit låsta:\n",
        "\n",
        "Vesica Piscis antas inte här\n",
        "\n",
        "Vesica Piscis förklaras inte här\n",
        "\n",
        "Vesica Piscis bevisas inte här\n",
        "\n",
        "\n",
        "Denna notebook är en operativ visualisering av en relation\n",
        "som är formellt etablerad före all kod."
      ],
      "metadata": {
        "id": "cBr9SefJAHuu"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "import numpy as np\n",
        "import matplotlib.pyplot as plt\n"
      ],
      "metadata": {
        "id": "r5fgHHcfAHDi"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "theta = np.linspace(0, 2 * math.pi, 1000)\n",
        "\n",
        "x1 = RADIUS * np.cos(theta)\n",
        "y1 = RADIUS * np.sin(theta)\n",
        "\n",
        "x2 = DISTANCE + RADIUS * np.cos(theta)\n",
        "y2 = RADIUS * np.sin(theta)\n"
      ],
      "metadata": {
        "id": "CJ9x4AxGANXn"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Representationsdeklaration — cirklar\n",
        "\n",
        "De cirklar som introduceras nedan är **inte konstruktioner av Vesica Piscis**.\n",
        "\n",
        "De är:\n",
        "\n",
        "- valda som **representation**\n",
        "- fixerade för **visualisering**\n",
        "- utan fri parameter\n",
        "- utan etablerande funktion\n",
        "\n",
        "Ingen geometrisk relation skapas här.\n",
        "Relationen antas redan vara giltig.\n"
      ],
      "metadata": {
        "id": "3coqXNFcU85A"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "plt.figure(figsize=(6, 6))\n",
        "plt.plot(x1, y1)\n",
        "plt.plot(x2, y2)\n",
        "plt.gca().set_aspect(\"equal\", adjustable=\"box\")\n",
        "plt.title(\"STEG 0: Vesica Piscis\")\n",
        "plt.axis(\"off\")\n",
        "plt.show()\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 369
        },
        "id": "GgVuJNARAOUN",
        "outputId": "3ba09b01-ac3c-4a36-b998-030e5e6cded5"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 600x600 with 1 Axes>"
            ],
            "image/png": 
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "import math\n",
        "import numpy as np\n",
        "import matplotlib.pyplot as plt\n",
        "\n",
        "RADIUS = 1.0\n",
        "DISTANCE = 1.0\n",
        "\n",
        "theta = np.linspace(0, 2 * math.pi, 1000)\n",
        "\n",
        "# Cirklar\n",
        "x1 = RADIUS * np.cos(theta)\n",
        "y1 = RADIUS * np.sin(theta)\n",
        "\n",
        "x2 = DISTANCE + RADIUS * np.cos(theta)\n",
        "y2 = RADIUS * np.sin(theta)\n",
        "\n",
        "# Centrum\n",
        "c1 = (0.0, 0.0)\n",
        "c2 = (DISTANCE, 0.0)\n",
        "cm = (DISTANCE / 2.0, 0.0)\n",
        "\n",
        "plt.figure(figsize=(6, 6))\n",
        "plt.plot(x1, y1)\n",
        "plt.plot(x2, y2)\n",
        "\n",
        "plt.scatter([c1[0], c2[0], cm[0]], [c1[1], c2[1], cm[1]], zorder=3)\n",
        "\n",
        "plt.gca().set_aspect(\"equal\", adjustable=\"box\")\n",
        "plt.title(\"Bild 2 — Centrum-noder\")\n",
        "plt.axis(\"off\")\n",
        "plt.show()\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 369
        },
        "id": "P516CGHEBA7X",
        "outputId": "c3e83f84-3969-4317-d355-be9493acbef3"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 600x600 with 1 Axes>"
            ],
            "image/png": 
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Intersektionspunkter för två cirklar med samma radie och avstånd = radie\n",
        "h = math.sqrt(3) / 2 * RADIUS\n",
        "ip1 = (DISTANCE / 2.0,  h)\n",
        "ip2 = (DISTANCE / 2.0, -h)\n",
        "\n",
        "plt.figure(figsize=(6, 6))\n",
        "plt.plot(x1, y1, alpha=0.5)\n",
        "plt.plot(x2, y2, alpha=0.5)\n",
        "\n",
        "# Centrum\n",
        "plt.scatter([c1[0], c2[0]], [c1[1], c2[1]], zorder=3)\n",
        "\n",
        "# Intersektioner\n",
        "plt.scatter([ip1[0], ip2[0]], [ip1[1], ip2[1]], zorder=4)\n",
        "\n",
        "plt.gca().set_aspect(\"equal\", adjustable=\"box\")\n",
        "plt.title(\"Bild 3 — Intersektionspunkter\")\n",
        "plt.axis(\"off\")\n",
        "plt.show()\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 369
        },
        "id": "T2B0Wn6_BEwi",
        "outputId": "801e8b10-6e25-456b-81b5-e74bf2edbd31"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 600x600 with 1 Axes>"
            ],
            "image/png": 
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Irrationell höjd i Vesica Piscis\n",
        "h = math.sqrt(3) / 2 * RADIUS\n",
        "\n",
        "plt.figure(figsize=(6, 6))\n",
        "plt.plot(x1, y1, alpha=0.3)\n",
        "plt.plot(x2, y2, alpha=0.3)\n",
        "\n",
        "# Vertikal linje som visar irrationell höjd\n",
        "plt.plot(\n",
        "    [DISTANCE / 2.0, DISTANCE / 2.0],\n",
        "    [-h, h],\n",
        "    linestyle=\"--\"\n",
        ")\n",
        "\n",
        "# Centrum\n",
        "plt.scatter([c1[0], c2[0]], [c1[1], c2[1]], zorder=3)\n",
        "\n",
        "# Intersektioner\n",
        "plt.scatter([ip1[0], ip2[0]], [ip1[1], ip2[1]], zorder=4)\n",
        "\n",
        "plt.gca().set_aspect(\"equal\", adjustable=\"box\")\n",
        "plt.title(\"Bild 4 — Irrationell funktion (√3 / 2)\")\n",
        "plt.axis(\"off\")\n",
        "plt.show()\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 369
        },
        "id": "-RT3H_YDPVH7",
        "outputId": "c3cd33cc-8767-4fb0-c8cc-db4494560fae"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 600x600 with 1 Axes>"
            ],
            "image/png": 
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "scales = [0.5, 1.0, 2.0, 5.0]\n",
        "ratios = []\n",
        "\n",
        "for s in scales:\n",
        "    h_s = math.sqrt(3) / 2 * s\n",
        "    ratios.append(h_s / s)\n",
        "\n",
        "plt.figure(figsize=(6, 4))\n",
        "plt.plot(scales, ratios, marker=\"o\")\n",
        "plt.axhline(math.sqrt(3) / 2, linestyle=\"--\")\n",
        "\n",
        "plt.xlabel(\"Skala\")\n",
        "plt.ylabel(\"Höjd / Radie\")\n",
        "plt.title(\"Bild 5 — Irrationell funktion är skaloberoende\")\n",
        "plt.grid(True)\n",
        "plt.show()\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 410
        },
        "id": "gsh23ABqPZem",
        "outputId": "2633344a-463e-41ec-ce66-57f24deec0c2"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 600x400 with 1 Axes>"
            ],
            "image/png": 
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Två raka sträckor med samma längd (1.0)\n",
        "straight_a = RADIUS          # radie\n",
        "straight_b = DISTANCE        # centrumavstånd\n",
        "\n",
        "# Den relationellt uppkomna höjden\n",
        "h = math.sqrt(3) / 2 * RADIUS\n",
        "\n",
        "# Absolut och relativ skillnad\n",
        "absolute_diff = abs(straight_a - h)\n",
        "relative_diff = absolute_diff / straight_a\n",
        "\n",
        "{\n",
        "    \"rak_stracka_A\": straight_a,\n",
        "    \"rak_stracka_B\": straight_b,\n",
        "    \"relationell_hojd\": h,\n",
        "    \"absolut_skillnad\": absolute_diff,\n",
        "    \"relativ_skillnad\": relative_diff\n",
        "}\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "_mBt9qC-QIxe",
        "outputId": "8c7abb8b-814c-44e6-c140-c7e651a6a760"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "{'rak_stracka_A': 1.0,\n",
              " 'rak_stracka_B': 1.0,\n",
              " 'relationell_hojd': 0.8660254037844386,\n",
              " 'absolut_skillnad': 0.1339745962155614,\n",
              " 'relativ_skillnad': 0.1339745962155614}"
            ]
          },
          "metadata": {},
          "execution_count": 9
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "plt.figure(figsize=(6, 6))\n",
        "\n",
        "# Baslinje (rak sträcka)\n",
        "plt.plot([0, 1], [0, 0], linewidth=3)\n",
        "\n",
        "# Relationell höjd\n",
        "plt.plot([0.5, 0.5], [0, h], linewidth=3)\n",
        "\n",
        "# Markeringar\n",
        "plt.scatter([0, 1], [0, 0], zorder=3)\n",
        "plt.scatter([0.5], [h], zorder=4)\n",
        "\n",
        "plt.gca().set_aspect(\"equal\", adjustable=\"box\")\n",
        "plt.title(\"Bild 6–7 — Samma längd, olika resultat\")\n",
        "plt.axis(\"off\")\n",
        "plt.show()\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 462
        },
        "id": "XoFujQ2cQSLq",
        "outputId": "d6ba3dbe-b10e-4eac-c9aa-8dc53164f33c"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 600x600 with 1 Axes>"
            ],
            "image/png": 
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Fyra primära riktningar/funktioner runt centralpunkten\n",
        "# (utan operatorer, utan dynamik)\n",
        "\n",
        "cx, cy = cm  # centralpunkt (mitt mellan centrum)\n",
        "\n",
        "directions = {\n",
        "    \"in\":    (cx, cy - h),\n",
        "    \"out\":   (cx, cy + h),\n",
        "    \"left\":  (cx - RADIUS/2, cy),\n",
        "    \"right\": (cx + RADIUS/2, cy)\n",
        "}\n",
        "\n",
        "plt.figure(figsize=(6, 6))\n",
        "plt.plot(x1, y1, alpha=0.3)\n",
        "plt.plot(x2, y2, alpha=0.3)\n",
        "\n",
        "# Centralpunkt\n",
        "plt.scatter([cx], [cy], zorder=5)\n",
        "\n",
        "# Fyra grundfunktioner (geometriska riktningar)\n",
        "for p in directions.values():\n",
        "    plt.plot([cx, p[0]], [cy, p[1]], linewidth=2)\n",
        "\n",
        "plt.gca().set_aspect(\"equal\", adjustable=\"box\")\n",
        "plt.title(\"Bild 8 — Fyra grundfunktioner (centralisering)\")\n",
        "plt.axis(\"off\")\n",
        "plt.show()\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 369
        },
        "id": "f-eJwiY8Qh3z",
        "outputId": "603737f5-01c8-4950-cdd1-95a29b384f80"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 600x600 with 1 Axes>"
            ],
            "image/png": 
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Sju stabila noder i Nivå I\n",
        "nodes_x = [\n",
        "    c1[0],      # vänster centrum\n",
        "    c2[0],      # höger centrum\n",
        "    ip1[0],     # övre intersektion\n",
        "    ip2[0],     # nedre intersektion\n",
        "    cm[0],      # centralpunkt\n",
        "    c1[0] - RADIUS,  # vänster yttergräns\n",
        "    c2[0] + RADIUS   # höger yttergräns\n",
        "]\n",
        "\n",
        "nodes_y = [\n",
        "    c1[1],\n",
        "    c2[1],\n",
        "    ip1[1],\n",
        "    ip2[1],\n",
        "    cm[1],\n",
        "    0.0,\n",
        "    0.0\n",
        "]\n",
        "\n",
        "plt.figure(figsize=(6, 6))\n",
        "plt.plot(x1, y1, alpha=0.3)\n",
        "plt.plot(x2, y2, alpha=0.3)\n",
        "\n",
        "plt.scatter(nodes_x, nodes_y, zorder=5)\n",
        "\n",
        "plt.gca().set_aspect(\"equal\", adjustable=\"box\")\n",
        "plt.title(\"Bild 9 — Sju tillåtna noder (Nivå I)\")\n",
        "plt.axis(\"off\")\n",
        "plt.show()\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 371
        },
        "id": "TunDSSBdQoXw",
        "outputId": "b74ddeb2-8041-4d39-bbb8-f6f6310128b3"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 600x600 with 1 Axes>"
            ],
            "image/png": 
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Absolut och procentuell relation mellan rak sträcka och relationell höjd\n",
        "\n",
        "rak_stracka = RADIUS                 # referenslängd = 1.0\n",
        "relationell_hojd = math.sqrt(3) / 2 * RADIUS\n",
        "\n",
        "absolut_relation = relationell_hojd - rak_stracka\n",
        "procent_relation = (absolut_relation / rak_stracka) * 100.0\n",
        "\n",
        "{\n",
        "    \"rak_stracka\": rak_stracka,\n",
        "    \"relationell_hojd\": relationell_hojd,\n",
        "    \"absolut_relation\": absolut_relation,\n",
        "    \"procentuell_relation\": procent_relation\n",
        "}\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "zI72ZirsRG3T",
        "outputId": "65aeaa42-b81a-4d51-85cf-d772d826c263"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "{'rak_stracka': 1.0,\n",
              " 'relationell_hojd': 0.8660254037844386,\n",
              " 'absolut_relation': -0.1339745962155614,\n",
              " 'procentuell_relation': -13.397459621556141}"
            ]
          },
          "metadata": {},
          "execution_count": 13
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "plt.figure(figsize=(6, 4))\n",
        "\n",
        "labels = [\"Rak sträcka (100%)\", \"Relationell höjd\"]\n",
        "values = [rak_stracka, relationell_hojd]\n",
        "\n",
        "plt.bar(labels, values)\n",
        "plt.axhline(rak_stracka, linestyle=\"--\")\n",
        "\n",
        "plt.title(\"Procentuell relation: rak sträcka vs relationell höjd\")\n",
        "plt.ylabel(\"Längd\")\n",
        "plt.show()\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 391
        },
        "id": "C8p6GsbzRL-a",
        "outputId": "e8de8d96-74d4-4924-fc09-e4cb9c7ad48b"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 600x400 with 1 Axes>"
            ],
            "image/png": 
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Försök att lägga till en åttonde nod inom samma klass (Nivå I)\n",
        "# Vi placerar den symmetriskt på vertikalaxeln bortom intersektionspunkterna\n",
        "\n",
        "attempt_8 = (cm[0], 2 * h)\n",
        "\n",
        "plt.figure(figsize=(6, 6))\n",
        "plt.plot(x1, y1, alpha=0.3)\n",
        "plt.plot(x2, y2, alpha=0.3)\n",
        "\n",
        "# Befintliga sju noder\n",
        "plt.scatter(nodes_x, nodes_y, zorder=5)\n",
        "\n",
        "# Försökt åttonde nod\n",
        "plt.scatter([attempt_8[0]], [attempt_8[1]], marker=\"x\", s=120, zorder=6)\n",
        "\n",
        "plt.gca().set_aspect(\"equal\", adjustable=\"box\")\n",
        "plt.title(\"Bild 10 — Försök till åttonde nod (klassbrott)\")\n",
        "plt.axis(\"off\")\n",
        "plt.show()\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 482
        },
        "id": "seU0ATooRWts",
        "outputId": "b7271b6d-60ea-4f7d-fd9f-23b1a66fed2c"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 600x600 with 1 Axes>"
            ],
            "image/png":
          },
          "metadata": {}
        }
      ]
    }
  ]
}

`````

